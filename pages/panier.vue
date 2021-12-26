<template>
    <div>
        <h1 class="fst-italic text-center my-5">Panier</h1>

        <h2 class="mb-5">Produit dans mon panier</h2>

        <div class="row row-cols-1 row-cols-md-3 g-4">
            <Produit v-for="product in panier" :key="product.id" :name="product.name" :price="product.price" v-on:affichage="supprimerProduit" role="affichager" />
        </div>
    </div>
</template>

<script>
import Produit from '@/components/Produit.vue'

export default {
    components: {
      Produit
    },

    data(){
        return {
            panier: []
        }
    },

    mounted() {
        
        const panier = JSON.parse(localStorage.getItem('cartItem'));

        this.panier = panier;
    },

    methods:{
        supprimerProduit(i){
            
            const panier = JSON.parse(localStorage.getItem('cartItem'));

            panier.splice(i, 1);
            localStorage.setItem('cartItem', JSON.stringify(panier));
            document.location.reload();

            //alert('Produit supprimé du panier !');
        }
    }
}
</script>
<template>
    <div>
        <h1 class="fst-italic text-center my-5">Commander</h1>

        <h2 class="mb-5">Produit disponibles</h2>

        <div class="row row-cols-1 row-cols-md-3 g-4">
            <Produit v-for="product in products" :key="product.id" :name="product.name" :price="product.price" v-on:commande="ajouterProduit" role="commander" />
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
            products: [
                { name: "Ice cream", price:"2.1" },
                { name: "Eggs", price:"1.8" },
                { name: "Beef", price:"4.5" },
                { name: "Coke Zero", price:"1.1" },
                { name: "Apple", price:"2.4" },
                { name: "Chicken", price:"3.6" },
                { name: "Cheese", price:"2.1" },
                { name: "Pasta", price:"1.6" },
                { name: "Milk", price:"1.1" },
                { name: "Yogurt", price:"2.2" },
                { name: "Carrot", price:"0.9" },
                { name: "Tomato", price:"1.0" },
            ]
        }
    },

    methods:{
        ajouterProduit(name, price){

            //const panier = [];
            const panier = JSON.parse(localStorage.getItem('cartItem')) || [];

            const item = {
                name : name,
                price: price
            };
            
            panier.push(item);

            alert('Produit ajouté au panier !');
            
            localStorage.setItem('cartItem', JSON.stringify(panier));
        }
    }
}
</script>

<style scoped>

</style>
<template>
    <div class="col">
    <div class="card">
        <img src="@/assets/images/shop-image.jpg" class="card-img-top" alt="Shop image">
        <div class="card-body">
            <h5 class="card-title">{{ name }}</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <p><span>{{ price }}</span></p>
            <a href="#" class="btn btn-primary">Ajouter au panier</a>
        </div>
    </div>
    </div>
</template>

<script>
export default {
    name: "Produit",
    props: ["name", "price", "role"]
}
</script>

<style scoped>
    .card {
        margin-bottom: 4rem;
    }
</style>
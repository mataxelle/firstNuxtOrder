<template>
    <div class="card" style="width: 18rem;">
        <img src="#" class="card-img-top" alt="#">
        <div class="card-body">
            <h5 class="card-title">{{ name }}</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <p><span>{{ price }}</span></p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "Produit",
    props: ["name", "price", "role"]
}
</script>
<template>
  <div>
    <div class="jumbotron my-5 change_background">
      <h1 class="display-4">Bienvenue et bonjour, à tous!</h1>
      <p class="lead">Profitez dès à présent de tout l'univers NuxtOrder !!</p>
      <hr class="my-4" />
      <p>Avec NuxtOrder, je consomme local.</p>
      <nuxt-link class="btn btn-outline-light btn-lg" to="/commandes" role="button"
        >Commander</nuxt-link
      >
    </div>

    <h2>Nos services</h2>

    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4">
      <div class="col mb-4">
        <div class="card h-100">
          <img
            src="@/assets/images/service-image1.jpg"
            class="card-img-top"
            alt="Service image"
          />
          <div class="card-body">
            <h5 class="card-title">Vendeurs partenaires</h5>
            <p class="card-text">
              This is a longer card with supporting text below as a natural
              lead-in to additional content. This content is a little bit
              longer.
            </p>
          </div>
          <div class="card-footer">
            <p class="text-right">
              <a href="#" class="text-primary">En savoir plus ></a>
            </p>
          </div>
        </div>
      </div>
      <div class="col mb-4">
        <div class="card h-100">
          <img
            src="@/assets/images/service-image2.png"
            class="card-img-top"
            alt="Service image"
          />
          <div class="card-body">
            <h5 class="card-title">Satisfait ou remboursé</h5>
            <p class="card-text">This is a short card.</p>
          </div>
          <div class="card-footer">
            <p class="text-right">
              <a href="#" class="text-primary">En savoir plus ></a>
            </p>
          </div>
        </div>
      </div>
      <div class="col mb-4">
        <div class="card h-100">
          <img
            src="@/assets/images/service-image1.jpg"
            class="card-img-top"
            alt="Service image"
          />
          <div class="card-body">
            <h5 class="card-title">Livraison express</h5>
            <p class="card-text">
              This is a longer card with supporting text below as a natural
              lead-in to additional content.
            </p>
          </div>
          <div class="card-footer">
            <p class="text-right">
              <a href="#" class="text-primary">En savoir plus ></a>
            </p>
          </div>
        </div>
      </div>
      <div class="col mb-4">
        <div class="card h-100">
          <img
            src="@/assets/images/service-image2.png"
            class="card-img-top"
            alt="Service image"
          />
          <div class="card-body">
            <h5 class="card-title">Tous nos services</h5>
            <p class="card-text">
              This is a longer card with supporting text below as a natural
              lead-in to additional content. This content is a little bit
              longer.
            </p>
          </div>
          <div class="card-footer">
            <p class="text-right">
              <a href="#" class="text-primary">En savoir plus ></a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.change_background {
  background-image: url("@/assets/images/vegetables.jpg");
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  color: white;
}
</style>

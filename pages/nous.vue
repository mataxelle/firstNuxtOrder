<template>
  <div>
    <h1 class="fst-italic text-center my-5">Notre enseigne</h1>

    <div class="row">
      <div class="col-md col-xs">
        <h2 class="my-5">Nos engagements</h2>
        <p>
          Depuis février 2017, nous avons baissé en moyenne de -9,40% le prix de
          vente de vos 1 050 articles de marques préférées et des 300 articles
          de marques Carrefour les plus achetés.
        </p>
      </div>

      <div class="col-md col-xs">
        <h2 class="my-5">Les paiements acceptés</h2>
        <p>Dans tous nos magasins, nous acceptons les paiements suivants :</p>
        <img src="@/assets/images/card-image1.png" alt="Card image">
        <img src="@/assets/images/card-image2s.png" alt="Card image">
      </div>
    </div>

    <h2 class="my-5">Nos magasins</h2>
    <div class="row row-cols-1 row-cols-md-2 g-4 my-5">
      <div class="col">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Magasin Nord</h5>
            <p class="card-text text-black-50">Avenue Nord</p>
            <p class="font-italic">Horaire d'ouverture</p>
            <table>
                <tr>
                    <td>lun-sam</td>
                    <td>08h00 à 19h30</td>
                </tr>
            </table>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Magasin Est</h5>
            <p class="card-text text-black-50">Avenue Est</p>
            <p class="font-italic">Horaire d'ouverture</p>
            <table>
                <tr>
                    <td>lun-sam</td>
                    <td>08h00 à 19h30</td>
                </tr>
            </table>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Magasin Sud</h5>
            <p class="card-text text-black-50">Avenue Sud</p>
            <p class="font-italic">Horaire d'ouverture</p>
            <table>
                <tr>
                    <td>lun-sam</td>
                    <td>08h00 à 19h30</td>
                </tr>
            </table>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Magasin Ouest</h5>
            <p class="card-text text-black-50">Avenue Ouest</p>
            <p class="font-italic">Horaire d'ouverture</p>
            <table>
                <tr>
                    <td>lun-sam</td>
                    <td>08h00 à 19h30</td>
                </tr>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
h5 {
    color: rgb(29, 8, 150);
}
</style>
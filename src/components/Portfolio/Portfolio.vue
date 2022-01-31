<template>
  <div id="portfolio" class="text-center">
    <h1>Portfolio</h1>
    <br />
    <div class="container">
      <div class="row">
        <div class="col">
          <img
            :src="require('@/assets/img/tablet.jpg')"
            class="img-fluid rounded"
            id="portfolio-img"
          />
        </div>
        <div class="col">
          <img
            :src="require('@/assets/img/skincare.gif')"
            class="img-fluid rounded"
            id="portfolio-img"
          />
        </div>
        <div class="col">
          <img
            :src="require('@/assets/img/bulb-idea.jpg')"
            class="img-fluid rounded"
            id="portfolio-img"
          />
        </div>
      </div>
      <br />

      <div class="row">
        <div class="col">
          <img
            :src="require('@/assets/img/social-media-metrics.jpg')"
            class="img-fluid rounded"
            id="portfolio-img"
          />
        </div>
        <div class="col">
          <img
            :src="require('@/assets/img/colour-mix.jpg')"
            class="img-fluid rounded"
            id="portfolio-img"
          />
        </div>
        <div class="col">
          <img
            :src="require('@/assets/img/tablet.jpg')"
            class="img-fluid rounded"
            id="portfolio-img"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
#portfolio {
  padding-top: 7%;
}
</style>

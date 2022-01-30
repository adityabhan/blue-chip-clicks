<template>
  <div id="about-us">
    <div>
      <div class="row">
        <div class="col">
          <br /><br />
          <h5>ABOUT US</h5>
          <br />
          <h2>We always provied best features to Clients</h2>
          <small>
            Blue Chip Clicks is an initiative started by a bunch of optimistic
            people offering clients to take their offline goodwill to the online
            platform driven by generating quality.
          </small>

          <br /><br />
          <button type="button" class="btn btn-warning">Read More</button>
        </div>

        <div class="col">
          <img
            id="about-image"
            class="img-fluid"
            :src="require('@/assets/img/about-capture.png')"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
#about-us {
  /* background-image: url("~@/assets/img/about-background.png"); */
  background: #1b335a;
  color: white;
  padding-left: 7%;
  padding-top: 5%;
  /* padding-bottom: 7%; */
}

#about-image {
  height: 70%;
  /* padding-left: 30%; */
}
</style>

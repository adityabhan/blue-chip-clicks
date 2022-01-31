<template>
  <div id="services">
    <div class="text-center">
      <h1>Services</h1>
      <br />
      <div class="container">
        <div class="row">
          <div
            class="col-lg-3 col-md-5 col-sm-10 offset-md-0 offset-sm-1 px-0 rounded"
          >
            <div class="image">
              <img :src="require('@/assets/img/ads-logo.jpg')" alt="" />
              <div class="overlay">
                <p class="h4" style="color:black;">Google Ads</p>
                <p class="textmuted" style="color:black;">
                  Running google ads to increase targeted reach.
                </p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>

          <div
            class="col-lg-3 col-md-5 col-sm-10 offset-md-0 offset-sm-1 px-0 rounded"
          >
            <div class="image">
              <img :src="require('@/assets/img/social-media.jpg')" alt="" />
              <div class="overlay">
                <!-- <p class="amount">$399</p> -->
                <p class="h4">Social Media Marketing</p>
                <p class="textmuted">
                  Marketing your products to create an impact
                </p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-5 col-sm-10 offset-md-0 offset-sm-1 px-0">
            <div class="image">
              <img :src="require('@/assets/img/website-dev.jpg')" alt="" />
              <div class="overlay">
                <p class="h4">Website Development</p>
                <p class="textmuted" style="color: white">
                  A short description of the same.
                </p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-5 col-sm-10 offset-md-0 offset-sm-1 px-0">
            <div class="image">
              <img :src="require('@/assets/img/logo-dev.jpg')" alt="" />
              <div class="overlay">
                <p class="h4" style="color: black">Logo designing</p>
                <p class="textmuted">A short description of the same.</p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <br />
        <br />

        <div class="row">
          <div class="col-lg-4 col-md-6 col-sm-10 offset-md-0 offset-sm-1 px-0">
            <div class="image">
              <img :src="require('@/assets/img/seo.png')" alt="" />
              <div class="overlay">
                <p class="h4" style="color: black">
                  Search Engine Optimization
                </p>
                <p class="textmuted">
                  We will make sure people come to know you.
                </p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 col-sm-10 offset-md-0 offset-sm-1 px-0">
            <div class="image">
              <img :src="require('@/assets/img/product-design.jpg')" alt="" />
              <div class="overlay">
                <p class="h4" style="color: black">Product Design</p>
                <p class="textmuted">
                  Have a new Idea? We will help you design it.
                </p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 col-sm-10 offset-md-0 offset-sm-1 px-0">
            <div class="image">
              <img :src="require('@/assets/img/photo-shoot.jpg')" alt="" />
              <div class="overlay">
                <p class="h4" style="color: black">Photoshoot and Videos</p>
                <p class="textmuted">
                  Elevate product experience with our in house Photoshoot and
                  video editing.
                </p>
                <ul class="list-unstyled d-flex">
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                  <li><span class="fas fa-star"></span></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.services-icon {
  font-size: 700%;
}

#services {
  padding-top: 5%;
}

@import url("https://fonts.googleapis.com/css2?family=Open+Sans&display=swap");

* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: "Open Sans", sans-serif;
}

body {
  background-color: turquoise;
}

p {
  margin: 0;
}

img {
  width: 100%;
  height: 300px;
}

.container {
  margin: 25px auto;
}

.image {
  position: relative;
  width: 100%;
  overflow: hidden;
}

.image .overlay {
  position: absolute;
  bottom: 0;
  padding-left: 25px;
  padding-top: 15px;
  width: 100%;
  color: white;
  font-size: 20px;
  z-index: 5;
}

.image .overlay::before {
  content: "";
  background: #ffff;
  height: 100%;
  width: 100%;
  z-index: 1;
  position: absolute;
  left: 0;
  bottom: -150px;
  z-index: -2;
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.image:hover .overlay {
  color: black;
}

.container .image:hover .overlay .amount,
.container .image:hover .overlay .h4,
.container .image:hover .overlay .textmuted,
.container .image:hover .overlay .fa-star,
.container .image:hover .overlay .fa-star-half-alt,
.container .image:hover .overlay .review {
  color: black;
}

.image:hover .overlay::before {
  bottom: 0px;
}

.amount {
  font-size: 15px;
}

.textmuted {
  color: #f8f8f8;
  font-weight: 200;
  font-size: 15px;
  text-transform: capitalize;
}

.fa-star,
.fa-star-half-alt {
  color: white;
  font-size: 10px;
  margin: 0 1px;
}

.review {
  font-size: 12px;
  font-weight: 200;
}
</style>

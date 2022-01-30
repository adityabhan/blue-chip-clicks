<template>
  <div id="nav-bar">
    <div>
      <nav
        class="navbar fixed-top navbar-expand-lg navbar-light nav-fill"
        style="background: white"
      >
        <div class="container-fluid">
          <img
            :src="require('@/assets/img/blue-chip-white1.jpg')"
            alt="Blue Chip Clicks"
            width="170"
            height="50"
            class="d-inline-block align-text-top"
          />

          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse justify-content-end"
            id="navbarNav"
          >
            <ul class="navbar-nav nav-fill">
              <li class="nav-item">
                <a
                  @click="activate(1)"
                  :class="{ active: active_el == 1 }"
                  class="nav-link"
                  aria-current="page"
                  href="#"
                  >Home</a
                >
              </li>
              <li class="nav-item">
                <a
                  class="nav-link"
                  @click="activate(2)"
                  :class="{ active: active_el == 2 }"
                  href="#about-us"
                  >About</a
                >
              </li>
              <li class="nav-item">
                <a
                  class="nav-link"
                  @click="activate(3)"
                  :class="{ active: active_el == 3 }"
                  href="#services"
                  >Our Services+</a
                >
              </li>

              <li class="nav-item">
                <a
                  class="nav-link"
                  @click="activate(4)"
                  :class="{ active: active_el == 4 }"
                  href="#contact"
                  >Contact Us</a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      active_el: 0,
    };
  },
  methods: {
    activate(el) {
      this.active_el = el;
      // console.log(this.active_el);
    },
  },
};
</script>

<style scoped>
#nav-bar {
  /* padding-left: 10%;
  padding-right: 10%; */
  /* position: fixed; */
  /* background: red; */
}

li.nav-item:hover > a {
  border-bottom: 2px solid #e86c16;
}

li.nav-item .active {
  border-bottom: 2px solid #e86c16;
}
</style>

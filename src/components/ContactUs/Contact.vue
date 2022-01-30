<template>
  <div id="contact">
    <h1>Ready to start Project?</h1>

    <div class="row g-3">
      <div class="col-md-6">
        <input
          type="text"
          class="form-control form-control-lg"
          v-model="Contact.name"
          placeholder="Name:"
        />
      </div>

      <div class="col-md-6">
        <input
          type="email"
          class="form-control form-control-lg"
          v-model="Contact.email"
          placeholder="Email:"
        />
      </div>
    </div>
    <br />

    <div class="col-md-12">
      <textarea
        class="form-control"
        rows="5"
        v-model="Contact.description"
        placeholder="Message:"
      ></textarea>
    </div>
    <br />
    <div class="col-md-6">
      <button @click="submit" type="button" class="btn btn-warning btn-lg">
        Send Message
      </button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      Contact: {
        name: "",
        email: "",
        description: "",
      },
    };
  },
  beforeCreate() {},
  methods: {
    submit() {
      //   console.log(this.Contact);
      alert(this.Contact.name);
    },
  },
};
</script>

<style scoped>
#contact {
  padding-top: 10%;
  padding-bottom: 5%;
  padding-left: 15%;
  padding-right: 15%;
}
</style>

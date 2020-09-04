<template>
  <div>
    <section class="section">
      <div class="container-fliud">
        <img
          alt="Vue logo"
          class="rounded-circle"
          src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/unique-boy-names-hendrix-1564144528.jpg?crop=0.797xw:1.00xh;0.0220xw,0&resize=220:*"
        />
        <h1>Software Developer</h1>
        <p>This is a fun project I built while learning vue.js and bootstrap</p>
        <button
          type="button"
          class="btn btn-primary btn-lg"
          data-toggle="modal"
          data-target=".bd-example-modal-lg"
        >
          Contact
        </button>
      </div>
    </section>

    <!-- modal for contact -->
    <section class="">
      <div
        class="modal fade bd-example-modal-lg"
        tabindex="-1"
        role="dialog"
        aria-labelledby="myLargeModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog modal-lg">
          <div class="modal-content">
            <contact />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import contact from "./includes/contact";

export default {
  name: "Lander",
  components: {
    contact,
  },
};
</script>

<style scoped>
.section {
  padding-top: 10%;
  padding-bottom: 10%;
}
</style>

<template>
  <div>
    <div class="columns">
      <div class="column">
        <section class="hero is-fullheight">
          <div class="hero-body">
            <div>
              <p class="title">Alex Billson</p>
              <p class="subtitle">Software Developer</p>
              <div>
                <a
                  class="button is-light"
                  target="_blank"
                  href="https://www.linkedin.com/in/alex-billson-69a0ba13b"
                  >LinkedIn</a
                >
                <a
                  class="button is-light"
                  target="_blank"
                  href="https://github.com/pielegacy"
                  >GitHub</a
                >
                <a
                  class="button is-light"
                  target="_blank"
                  href="mailto:alex_billson@outlook.com"
                  >Email</a
                >
              </div>
            </div>
          </div>
        </section>
        <section class="section">
          <div class="block">
            I'm a Software Developer based in Melbourne, Australia.
          </div>
          <div class="block">
            I strive to create scalable, reliable and modern full-stack web applications
            using a variety of technologies.
          </div>
        </section>
      </div>
      <div class="column">
        <img class="image" src="~/assets/me.jpg" />
      </div>
    </div>
    <footer>
      <samp>
        &copy; Alex Billson {{ new Date().getFullYear() }}, built in
        <a target="_blank" href="https://nuxtjs.org/">Nuxt.js</a>
      </samp>
    </footer>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import CompanyList from "../components/CompanyList.vue";

export default Vue.extend({
  components: { CompanyList },
});
</script>

<style scoped>
footer {
  text-align: center;
}
</style>
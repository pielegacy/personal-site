<template>
  <div class="container">
    <h1>Hi, I'm Alex.</h1>
    <div class="row">
      <div class="one-half column">
        <p>I'm a Software Developer based in Melbourne, Australia.</p>
        <p>
          By profession I'm primarily a full stack web developer, with proficiency in all
          things Microsoft .NET.
        </p>
        <p>
          Want to learn more about me? Maybe get in touch?
        </p>
        <ul>
          <li>
            Connect on
            <a
              target="_blank"
              href="https://www.linkedin.com/in/alex-billson-69a0ba13b"
              >LinkedIn</a
            >
          </li>
          <li>
            Browse my code on
            <a target="_blank" href="https://github.com/pielegacy">GitHub</a>
          </li>
          <li>
            Contact me via
            <a href="mailto:alex_billson@outlook.com">Email</a>
          </li>
        </ul>
      </div>
      <div class="one-half column">
        <img class="u-max-full-width" src="~/assets/me.jpg" />
      </div>
    </div>
    <footer>
      <samp>
        &copy; Alex Billson {{ new Date().getFullYear() }}, built in <a target="_blank" href="https://nuxtjs.org/">Nuxt.js</a>
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
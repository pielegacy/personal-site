<template>
  <div class="company-container">
    <img
      class="u-max-full-width"
      :src="require(`~/assets/logos/${this.company.code}.png`)"
      :title="this.company.name"
      :alt="`Company logo for ${this.company.code}`"
    />
  </div>
</template>

<script lang="ts">
import { CompanyRecord } from "../interface/CompanyRecord";

export default {
  props: ["company"]
};
</script>

<style>
    .company-container img {
        max-height: 64px;
    }
</style>
<template>
  <div class="row">
    <div
      class="four columns"
      v-for="company in this.workHistory"
      :key="company.code"
    >
      <company :company="company" />
    </div>
  </div>
</template>

<script lang="ts">
import { CompanyRecord } from "../interface/CompanyRecord";

interface Data {
  workHistory: CompanyRecord[];
}

export default {
  data(): Data {
    return {
      workHistory: [
        {
          code: "mecca",
          name: "MECCA Brands",
          link: "",
        },
        {
          code: "loome",
          name: "Loome Software",
          link: "",
        },
        {
          code: "bbs",
          name: "Broadband Solutions",
          link: "",
        },
      ],
    };
  },
};
</script>

<style>
</style>
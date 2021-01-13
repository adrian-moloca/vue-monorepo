<template>
  <div class="hello">
    <h1>{{title}}</h1>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "SampleComponent",
  props: {
    title: String
  }
});
</script>

<style>
    h1 {
        color: red;
    }
</style>
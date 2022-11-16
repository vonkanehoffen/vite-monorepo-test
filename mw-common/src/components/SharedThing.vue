<template>
  <div class="outer">
    <h1>I'm a shared component</h1>
    <Another />
  </div>
</template>

<script lang="ts">
import Another from "@/components/Another.vue";
export default {
  name: "SharedThing",
  components: {Another}
}
</script>

<style scoped>
  .outer {
    background: paleturquoise;
    border: hotpink 10px solid;
  }
</style>

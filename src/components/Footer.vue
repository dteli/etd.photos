<template>
  <footer>
    <p>
      <span>©{{ new Date().getFullYear() }} Eli T. Drumm</span> ⧸
      <span><router-link to="/metaabout">about this site</router-link></span>
    </p>
  </footer>
</template>

<script lang="ts">
export default {
  name: 'Footer'
}
</script>

<style scoped lang="scss">
@use '../css/vars' as v;
@use '../css/exts' as x;

footer {
  flex-grow: 0;
  margin: 0;
  padding: 1rem 1.6rem;
  background-color: v.$c-black;
  color: v.$c-white;
  font-size: 1.6rem;
  @extend %link-colors;
}
</style>

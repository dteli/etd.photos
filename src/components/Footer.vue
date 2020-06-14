<template>
  <footer>
    <p>
      <span>©{{ new Date().getFullYear() }} Eli T. Drumm</span>
    </p>
  </footer>
</template>

<script lang="ts">
export default {
  name: 'Footer'
}
</script>

<style scoped lang="scss">
@use '../css/vars';

footer {
  flex-grow: 0;
  margin: 0;
  padding: 1rem 1.6rem;
  background-color: vars.$c-black;
  color: vars.$c-white;
  font-size: 1.6rem;
}
</style>

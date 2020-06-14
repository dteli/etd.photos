<template>
  <div class="main-div about">
    <h1>about</h1>

    <h2>Intro</h2>
    <p>blurb</p>

    <h2>Cameras</h2>
    <p>blurb</p>

    <h2>Thoughts on photography</h2>
    <p>blurb</p>
  </div>
</template>

<script lang="ts">
export default {
  name: 'About'
}
</script>

<style scoped lang="scss">
h2 {
  margin-top: 3rem;
}

p+h2 {
  margin-top: 5rem;
}
</style>

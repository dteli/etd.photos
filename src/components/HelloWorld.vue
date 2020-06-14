<template>
  <div>
    <h1>please check back soon</h1>
    <h1>I am learning Vue</h1>
    <h2>along with its friends</h2>
    <h3>plus I'm self-hosting on a VPS</h3>
    <h1><em>altogether I guess I'm using/learning:</em></h1>
    <ul>
      <li>front-end / Vue
        <ul>
          <li>Vue proper (the logo is a nice shade of green)</li>
          <li>Vue Router (how are there so many features in this)</li>
          <li>Vuex probably (although Redux gave me enough problems)</li>
          <li>Vue CLI (was not expecting a dope UI here)</li>
          <li>Vetur (a/the VS code extension)</li>
        </ul>
      </li>
      <li>hosting
        <ul>
          <li>setting up a VPS and Arch and ssh and all (done this plenty before tho)</li>
          <li>nginx (cannot believe I got this to actually work even a little, idk why)</li>
          <li>certbot (with sweet nginx plugin)</li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  margin: 4rem 0 1rem;
}

h2 {
  margin: 2rem;
}

h3 {
  margin: 2rem;
}
// ul {
//   margin: 2rem 0 4rem;
//   padding: 0;
//   //list-style-position: inside;
// }
// li {
//   display: block;
//   margin: 0;
// }
a {
  color: #42b983;
}

p {
  font-size: 1.6rem;
}
</style>

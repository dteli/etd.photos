<template>
  <div>
    <dl class="contact-details">
      <dt>email</dt><dd><a href="mailto:etd@dte.li" target="_blank">etd@dte.li</a></dd>
      <dt>phone</dt><dd><a href="tel:+18082008440">+1 808 200 8440</a></dd>
    </dl>
    <dl class="contact-details">
      <dt>Twitter</dt><dd><a href="https://twitter.com/chartrex" target="_blank">@chartrex</a></dd>
      <dt>GitHub</dt><dd><a href="https://github.com/dteli" target="_blank">dteli</a></dd>
    </dl>
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class ContactDetails extends Vue {

}
</script>

<style scoped lang="scss">
dl {
  margin-top: 3rem;

  &+dl {
    margin-top: 5rem;
  }
}
</style>

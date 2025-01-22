<template>
<div>
<HeaderPage />
  <Tutorial/>
  <FooterPage />
</div>
</template>

<script>
import HeaderPage from '~/components/HeaderPage.vue'
import FooterPage from '~/components/FooterPage.vue'
export default {
  name: 'IndexPage',
  components: {
    HeaderPage,
    FooterPage
  }
}
</script>

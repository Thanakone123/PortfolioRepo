<template>
  <div>
    <PortforioContainer />
    <ButtonToTop />
  </div>
</template>

<script>
import PortforioContainer from './components/PortfolioContainer.vue'
import ButtonToTop from './components/HelperComponent/ButtonToTop.vue'
export default {
  name: 'App',
  components: {
    PortforioContainer,
    ButtonToTop
  }
}
</script>
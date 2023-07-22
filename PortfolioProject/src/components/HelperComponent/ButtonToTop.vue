<template>
    <v-btn @click="scrollToTop" id="scrollToTopButton" class="p-0">
      <img src="../../assets/icons/mafumafu-cute.gif" width="70" height="70">
    </v-btn>
</template>

<script>
export default {
  name: 'ScrollToTopButton',
  methods: {
    scrollToTop() {
      document.body.scrollTop = 0;
      document.documentElement.scrollTop = 0;
    }
  }
}
</script>

<style scoped>
#scrollToTopButton {
  position: fixed;
  bottom: 20px;
  right: 20px;
  padding: 10px;
  cursor: pointer;
}
</style>
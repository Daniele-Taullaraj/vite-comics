<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'


export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {
    }
  },
  methods: {

  },
  mounted() {
  }

}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style></style>


<!-- getImg(path) {
  let risultato = new URL("../assets/img/" + path, import.meta.url);
  return risultato.href;
}, -->


<!-- 
https://github.com/vuejs/awesome-vue -->


<!-- https://www.youtube.com/watch?v=PkgUm_rlJgI -->

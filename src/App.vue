<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
import MainContent from "./components/MainContent.vue";

export default {
  components: { AppHeader, AppFooter, MainContent },
};
</script>

<template>
  <AppHeader />
  <MainContent />
  <AppFooter />
</template>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>

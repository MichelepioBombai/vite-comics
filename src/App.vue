<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
import MainContent from "./components/MainContent.vue";
import CardsContainer from "./components/CardsContainer.vue";

export default {
  components: { AppHeader, AppFooter, MainContent, CardsContainer },
};
</script>

<template>
  <AppHeader />
  <MainContent />
  <CardsContainer />

  <AppFooter />
</template>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Rubik", sans-serif;
}

a {
  text-decoration: none;
  color: black;
}
</style>

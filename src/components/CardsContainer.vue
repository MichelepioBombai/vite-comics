<script>
export default {
  props: {
    img: String,
    title: String,
  },
};
</script>

<template>
  <div class="col-2">
    <img :src="img" alt="" />
    <h2>{{ title }}</h2>
  </div>
</template>

<style scoped>
img {
  width: 200px;
  height: 200px;
  margin-top: 30px;
}
h2 {
  color: white;
  font-size: 18px;
  margin-top: 15px;
}
</style>

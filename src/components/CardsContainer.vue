<script>
export default {
  props: {
    img: String,
    title: String,
  },
};
</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col-2">
        <img :src="img" alt="" />
        <h2>{{ title }}</h2>
      </div>
    </div>
  </div>
</template>

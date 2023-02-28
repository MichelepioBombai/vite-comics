<script>
export default {
  props: {
    thumb: string,
    series: string,
  },
};
</script>

<template>
  <div>
    <img :src="thumb" alt="" />
    <h2>{{ series }}</h2>
  </div>
</template>

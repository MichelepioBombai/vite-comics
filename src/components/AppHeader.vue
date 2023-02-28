<script>
export default {
  data() {
    return {
      links: [
        "CHARACTER",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP",
      ],
      image: "../assets/dc-logo.png",
    };
  },
};
</script>

<template>
  <header>
    <div>
      <div class="container d-flex justify-content-between pt-3 pb-3">
        <div>
          <img src="../assets/dc-logo.png" alt="" />
        </div>
        <div>
          <ul>
            <li v-for="link in links">
              <a href="#">{{ link }}</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
.bg-black {
  background-color: black;
  height: 43px;
}

ul li {
  list-style-type: none;
  font-size: 14px;
}

ul {
  display: flex;
  gap: 20px;
  padding-top: 30px;
}

a {
  text-decoration: none;
  color: black;
}

img {
  width: 80px;
}
</style>

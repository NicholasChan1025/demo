<template>
  <div class="home" :style="{ backgroundImage: `url(${img})` }">
    <div id="nav">
      <router-link to="/about">
        <b-button pill size="sm" variant="outline-light">About</b-button>
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      img: require("../assets/home.jpg"),
    };
  },
};
</script>
<style  scoped>
.home {
  height: 100%;
}
</style>
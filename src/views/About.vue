<template>
  <div class="about" :style="{ backgroundImage: `url(${img})` }">
    <div id="nav">
      <router-link to="/">
        <b-button pill size="sm" variant="outline-light">Home</b-button>
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      img: require("../assets/about.jpg"),
    };
  },
};
</script>
<style  scoped>
.about {
  height: 100%;
}
</style>
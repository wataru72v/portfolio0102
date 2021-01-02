<template>
  <div>
    <img class="skill" v-for="image in images" :src="image.path" />
  </div>
</template>

<style>
img.skill {
  width: 19%;
  margin: 3%;
}
</style>

<script>
export default {
  data() {
    return {
      images: [{ path: "/nodejs.png" }, { path: "/vuejs.png" }],
    };
  },
};
</script>

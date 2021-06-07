<template>
  <div class="home">
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_01.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_01.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_02.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_02.jpeg" alt="" />
    </picture>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>

<style scoped>
.picture img {
  display: block;
  width: 100%;
  margin: 0 auto;
  height: auto;
  max-width: 1400px;
}

.picture {
  position: relative;
  z-index: 0;
  left: 0;
}
</style>

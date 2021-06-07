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
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_03.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_03.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_04.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_04.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_05.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_05.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_06.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_06.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_07.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_07.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_08.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_08.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_09.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_09.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_10.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_10.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_11.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_11.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_12.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_12.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_13.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_13.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_14.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_14.jpeg" alt="" />
    </picture>
    <picture class="picture">
      <source
        media="(max-width: 767px)"
        srcset="../assets/img/ariel_MB_tw_15.jpeg"
      />
      <img src="../assets/img/ariel_PC_tw_15.jpeg" alt="" />
    </picture>
    <footer id="float">
      <img src="../assets/img/ariel_PC_tw_btn.png" alt="" />
    </footer>
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
html,
body {
  margin: 0 auto;
  padding: 0;
  background: #c0e7f8;
}

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

.buy {
  position: relative;
  width: 100%;
  max-width: 1400px;
}

#momo_btn_1 {
  position: absolute;
  display: block;
  top: 76%;
  left: 9.6%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#pchome_btn_1 {
  position: absolute;
  display: block;
  top: 76%;
  left: 29.1%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#momo_btn_2 {
  position: absolute;
  display: block;
  top: 76%;
  left: 51.9%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#pchome_btn_2 {
  position: absolute;
  display: block;
  top: 76%;
  left: 71.4%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#momo_btn_3 {
  position: absolute;
  display: block;
  top: 76%;
  left: 9.6%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#pchome_btn_3 {
  position: absolute;
  display: block;
  top: 76%;
  left: 29.1%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#momo_btn_4 {
  position: absolute;
  display: block;
  top: 76%;
  left: 51.9%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

#pchome_btn_4 {
  position: absolute;
  display: block;
  top: 76%;
  left: 71.4%;
  width: 19%;
  height: 15%;
  z-index: 10;
}

img {
  display: block;
}

footer {
  position: fixed;
  bottom: 0px;
  right: 0px;
  text-align: -webkit-right;
  margin-right: 10%;
  z-index: 999;
}

footer img {
  width: 70%;
}

@media screen and (max-width: 767px) {
  footer {
    width: 100%;
    position: fixed;
    bottom: 0px;
    right: 0;
    margin-right: 0;
    z-index: 999;
  }

  footer img {
    width: 100%;
  }

  #momo_btn_1 {
    position: absolute;
    display: block;
    top: 37.7%;
    left: 10.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #pchome_btn_1 {
    position: absolute;
    display: block;
    top: 37.7%;
    left: 51.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #momo_btn_2 {
    position: absolute;
    display: block;
    top: 86.8%;
    left: 10.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #pchome_btn_2 {
    position: absolute;
    display: block;
    top: 86.8%;
    left: 51.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #momo_btn_3 {
    position: absolute;
    display: block;
    top: 38.9%;
    left: 10.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #pchome_btn_3 {
    position: absolute;
    display: block;
    top: 38.9%;
    left: 51.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #momo_btn_4 {
    position: absolute;
    display: block;
    top: 88.6%;
    left: 10.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }

  #pchome_btn_4 {
    position: absolute;
    display: block;
    top: 88.6%;
    left: 51.6%;
    width: 39.5%;
    height: 6.5%;
    z-index: 10;
  }
}
</style>

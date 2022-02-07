<template>
  <section class="hero-container section-shaped">
    <div class="hero-container-video">
      <video height="100%" autoplay muted loop>
        <source src="https://siasky.net/AADdaFhjEKApSNnZvyzIvGEvKre7RiPWQ86Sq-VlDyrSSw" type="video/mp4">
      </video>
    </div>
    <b-row align-v="center" align-h="center" class="hero-container-section ml-0 mr-0">
      <b-col cols="12" md="8" class="px-4">
        <h1 class="display-3  text-white">
          Cumple todo lo que deseas
        </h1>
        <p class="lead  text-white">
          Mientras te diviertes, aprendes y conoces de otras culturas.
        </p>
      </b-col>
    </b-row>
  </section>
</template>
<style lang="scss">

.hero-container {
  position: relative;
  width: 100%;
  height: 120vh;

  &-video {
    position: absolute;
    top: -86px;
    bottom: 0;
    right: 0;
    left: 0;
    display: flex;
    justify-content: center;
    overflow: hidden;

    &::after {
      content: "";
      background: rgba(0, 0, 0, 0.7);
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
    }
  }

  &-section {
    height: 100%;
    text-align: center !important;
  }
}

</style>

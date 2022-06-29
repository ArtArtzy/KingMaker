<template>
  <div class="gt-xs lt-lg picShow-t">
    <q-responsive :ratio="37 / 9" style="width: 100%; max-width: 1400">
      <q-carousel
        animated
        v-model="slide"
        arrows
        navigation
        swipeable
        infinite
        :autoplay="autoplay"
        style="width: 100%"
      >
        <q-carousel-slide :name="1" class="no-padding">
          <img
            src="../../public/marketing/p01.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
        <q-carousel-slide :name="2" class="no-padding">
          <img
            src="../../public/marketing/p02.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
        <q-carousel-slide :name="3" class="no-padding">
          <img
            src="../../public/marketing/p03.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
      </q-carousel>
    </q-responsive>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 1,
      autoplay: true,
    };
  },
};
</script>

<style lang="scss" scoped>
.picShow {
  width: 100%;
  max-width: 1400px;
  margin: auto;
}
.picShow-t {
  width: 100%;
}
.slide-pc {
  overflow-y: hidden;
  background-color: white;
}
</style>

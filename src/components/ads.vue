<template>
  <div>
    <!-- pc -->
    <div class="picShow gt-md bg-white">
      <q-responsive :ratio="38.7 / 9" style="width: 100%; max-width: 1400">
        <q-carousel
          animated
          v-model="slide"
          arrows
          navigation
          infinite
          :autoplay="autoplay"
          class="slide-pc"
        >
          <q-carousel-slide :name="1" class="no-padding slide-pc">
            <img
              src="../../public/marketing/p01.jpg"
              alt=""
              style="width: 100%"
            />
          </q-carousel-slide>
          <q-carousel-slide :name="2" class="no-padding slide-pc">
            <img
              src="../../public/marketing/p02.jpg"
              alt=""
              style="width: 100%"
            />
          </q-carousel-slide>
          <q-carousel-slide :name="3" class="no-padding slide-pc">
            <img
              src="../../public/marketing/p03.jpg"
              alt=""
              style="width: 100%"
            />
          </q-carousel-slide>
        </q-carousel>
      </q-responsive>
    </div>
    <!-- tablet -->
    <div class="gt-xs lt-lg picShow-t">
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
            src="../../public/marketing/t01.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
        <q-carousel-slide :name="2" class="no-padding">
          <img
            src="../../public/marketing/t02.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
        <q-carousel-slide :name="3" class="no-padding">
          <img
            src="../../public/marketing/t03.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
      </q-carousel>
    </div>
    <!-- mobile -->
    <div class="lt-sm picShow-t">
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
            src="../../public/marketing/m01.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
        <q-carousel-slide :name="2" class="no-padding">
          <img
            src="../../public/marketing/m02.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
        <q-carousel-slide :name="3" class="no-padding">
          <img
            src="../../public/marketing/m03.jpg"
            alt=""
            style="width: 100%"
          />
        </q-carousel-slide>
      </q-carousel>
    </div>
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

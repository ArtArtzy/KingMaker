<template>
  <div class="picShow-t">
    <q-responsive :ratio="21.1 / 9" style="width: 100%; max-width: 1400">
      <q-carousel
        animated
        v-model="slide"
        arrows
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

<style lang="scss" scoped></style>

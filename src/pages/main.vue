<template>
  <div>
    <div class="mainDiv font-content gt-md">
      <main-menu />
      <ads-pc />
      <content-pc />
    </div>
    <div class="gt-xs lt-lg">
      <main-menu />
      <ads-t />
      <content-t />
    </div>
    <div class="lt-sm">
      <main-menu />
      <ads-m />
      <content-m />
    </div>
  </div>
</template>

<script>
import mainMenu from "../components/menu.vue";
import adsPc from "../components/ads_pc.vue";
import adsT from "../components/ads_t.vue";
import adsM from "../components/ads_m.vue";
import contentPc from "../components/content_pc.vue";
import contentT from "../components/content_t.vue";
import contentM from "../components/content_m.vue";
export default {
  components: { adsPc, contentPc, adsT, mainMenu, contentT, adsM, contentM },
};
</script>

<style lang="scss" scoped>
.mainDiv {
  width: 100%;
  max-width: 1400px;
  margin: auto;
  background-color: white;
}
</style>

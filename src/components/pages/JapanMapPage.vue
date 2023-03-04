<script setup lang="ts">
import JapanMap from "@/components/japan/JapanMap.vue";
</script>

<template>
  <div class="japan-map-page">
    <div class="japan-map-page-contents">
      <JapanMap></JapanMap>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.japan-map-page {
  position: relative;
  width: 768px;
  height: 768px;
}
.japan-map-page-contents {
  position: absolute;
  width: 100%;
  height: 100%;
}
.sample-image {
  position: absolute;
}
</style>

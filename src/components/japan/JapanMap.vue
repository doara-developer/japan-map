<script setup lang="ts">
import AomoriMap from "@/components/japan/prefecture/AomoriMap.vue";
</script>

<template>
  <div class="japan-map">
    <div class="japan-map-hokkaido"></div>
    <div class="japan-map-aomori">
      <AomoriMap></AomoriMap>
    </div>
    <div class="japan-map-iwate"></div>
    <div class="japan-map-akita"></div>
    <div class="japan-map-yamagata"></div>
    <div class="japan-map-miyagi"></div>
  </div>
</template>

<style lang="scss" scoped>
.japan-map {
  position: relative;
  width: 100%;
  height: 100%;
}
.japan-map-hokkaido {
  position: absolute;
  border: 1px solid black;
  width: 40.5%;
  height: 29.5%;
  left: 58.8%;
  top: 0%;
}
.japan-map-aomori {
  position: absolute;
  width: 8.9%;
  height: 8.45%;
  left: 59.75%;
  top: 28.4%;
}
.japan-map-iwate {
  position: absolute;
  border: 1px solid black;
  width: 7%;
  height: 11%;
  left: 63.8%;
  top: 35.3%;
}
.japan-map-akita {
  position: absolute;
  border: 1px solid black;
  width: 6.3%;
  height: 10.5%;
  left: 59%;
  top: 35.3%;
}
.japan-map-yamagata {
  position: absolute;
  border: 1px solid black;
  width: 5.6%;
  height: 8.8%;
  left: 58.3%;
  top: 44.1%;
}
.japan-map-miyagi {
  position: absolute;
  border: 1px solid black;
  width: 6.8%;
  height: 8%;
  left: 62.2%;
  top: 44.6%;
}
</style>

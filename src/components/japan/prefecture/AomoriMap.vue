<script setup lang="ts"></script>

<template>
  <div class="aomori-map">
    <div v-for="n in 40" :key="n" :class="'aomori-map-' + n"></div>
  </div>
</template>

<style lang="scss" scoped>
.aomori-map {
  position: relative;
  width: 100%;
  aspect-ratio: 178 /169;
}
.aomori-map-1 {
  @include map-outline;
  @include line-position(53%, 6.1%, 36deg);
  width: 23%;
}
.aomori-map-2 {
  @include map-outline;
  @include line-position(72.2%, 9%, -30deg);
  width: 15%;
}
.aomori-map-3 {
  @include map-outline;
  @include line-position(78%, 13%, 92deg);
  width: 15%;
}
.aomori-map-4 {
  @include map-outline;
  @include line-position(76.15%, 29%, 94deg);
  width: 17.5%;
}
.aomori-map-5 {
  @include map-outline;
  @include line-position(75.3%, 43%, 92deg);
  width: 17.5%;
}
.aomori-map-6 {
  @include map-outline;
  @include line-position(79.1%, 56%, 82deg);
  width: 10.5%;
}
.aomori-map-7 {
  @include map-outline;
  @include line-position(80.8%, 66.5%, 74deg);
  width: 12.8%;
}
.aomori-map-8 {
  @include map-outline;
  @include line-position(87.9%, 72.5%, 4deg);
  width: 7%;
}
.aomori-map-9 {
  @include map-outline;
  @include line-position(91.5%, 77.5%, 49deg);
  width: 13%;
}
.aomori-map-10 {
  @include map-outline;
  @include line-position(3%, 86%, -131deg);
  width: 6%;
}
.aomori-map-11 {
  @include map-outline;
  @include line-position(-0.8%, 80%, -90deg);
  width: 10%;
}
.aomori-map-12 {
  @include map-outline;
  @include line-position(-0.4%, 74%, -135deg);
  width: 5.5%;
}
.aomori-map-13 {
  @include map-outline;
  @include line-position(-1.8%, 67%, -53deg);
  width: 15%;
}
.aomori-map-14 {
  @include map-outline;
  @include line-position(8%, 61%, 0deg);
  width: 7%;
}
.aomori-map-15 {
  @include map-outline;
  @include line-position(12.5%, 58.5%, -35deg);
  width: 10.5%;
}
.aomori-map-16 {
  @include map-outline;
  @include line-position(15%, 49%, -75deg);
  width: 15%;
}
.aomori-map-17 {
  @include map-outline;
  @include line-position(23%, 41.3%, -15deg);
  width: 6%;
}
.aomori-map-18 {
  @include map-outline;
  @include line-position(19.5%, 37.3%, -135deg);
  width: 11%;
}
.aomori-map-19 {
  @include map-outline;
  @include line-position(19.5%, 32.3%, -55deg);
  width: 6.5%;
}
.aomori-map-20 {
  @include map-outline;
  @include line-position(20%, 27%, -80deg);
  width: 9%;
}
.aomori-map-21 {
  @include map-outline;
  @include line-position(24%, 25%, 20deg);
  width: 9.5%;
}
.aomori-map-22 {
  @include map-outline;
  @include line-position(31.5%, 25%, -35deg);
  width: 6%;
}
.aomori-map-23 {
  @include map-outline;
  @include line-position(35.5%, 24.5%, 30deg);
  width: 6%;
}
.aomori-map-24 {
  @include map-outline;
  @include line-position(37.5%, 28%, 60deg);
  width: 8%;
}
.aomori-map-25 {
  @include map-outline;
  @include line-position(38.5%, 35%, 85deg);
  width: 10%;
}
.aomori-map-26 {
  @include map-outline;
  @include line-position(39%, 42%, 85deg);
  width: 10%;
}
.aomori-map-27 {
  @include map-outline;
  @include line-position(41%, 49%, 65deg);
  width: 9.5%;
}
.aomori-map-28 {
  @include map-outline;
  @include line-position(46%, 52%, -30deg);
  width: 8%;
}
.aomori-map-29 {
  @include map-outline;
  @include line-position(49%, 47%, -90deg);
  width: 8%;
}
.aomori-map-30 {
  @include map-outline;
  @include line-position(51.5%, 42%, -40deg);
  width: 6.5%;
}
.aomori-map-31 {
  @include map-outline;
  @include line-position(55%, 42%, 30deg);
  width: 9%;
}
.aomori-map-32 {
  @include map-outline;
  @include line-position(61%, 47%, 45deg);
  width: 9.5%;
}
.aomori-map-33 {
  @include map-outline;
  @include line-position(60%, 39%, -75deg);
  width: 24%;
}
.aomori-map-34 {
  @include map-outline;
  @include line-position(69%, 24%, -110deg);
  width: 9%;
}
.aomori-map-35 {
  @include map-outline;
  @include line-position(61%, 25%, 140deg);
  width: 13%;
}
.aomori-map-36 {
  @include map-outline;
  @include line-position(51%, 30%, 170deg);
  width: 13%;
}
.aomori-map-37 {
  @include map-outline;
  @include line-position(47%, 30%, -130deg);
  width: 5.5%;
}
.aomori-map-38 {
  @include map-outline;
  @include line-position(37.5%, 14%, 103deg);
  width: 29%;
}
</style>

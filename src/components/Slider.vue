<template>
  <Vue3Marquee>
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/hRtkkf3/zen.png" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/41NwkHq/g3.png" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/FD1xGDR/dell.png" />
  </Vue3Marquee>
</template>

<script>
import { Vue3Marquee } from 'vue3-marquee'
import 'vue3-marquee/dist/style.css'

export default {
  components: {
    Vue3Marquee,
  },
}
</script>
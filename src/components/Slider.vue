<template>
  <Vue3Marquee>
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/x8QRfX6/dell.png" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/d6p65qh/g3.png" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/3FtqCbk/zen.png" />
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
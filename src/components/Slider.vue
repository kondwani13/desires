<template>
  <Vue3Marquee>
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/x3hHFz8/dell.png" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/3W1FNTH/g3.png" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/10q9tgn/zen.png" />
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
<template>
  <div class="Home">
    <!-- <con-menu /> -->
    <con-clip />
    <con-playlist />
    <con-emoji />
  </div>
</template>

<script>
import ConMenu from './ConMenu.vue'
import ConClip from './ConClip.vue'
import ConPlaylist from './ConPlaylist.vue'
import ConEmoji from './ConEmoji.vue'

export default {
  name: 'Home',
//   data () {
//     return {
//       msg: 'Welcome to Your Vue.js App'
//     }
//   },
  components: {
    ConMenu,
    ConClip,
    ConPlaylist,
    ConEmoji,
  }
}
</script>

<style>
</style>

<template>
  <section>
    <TopNav></TopNav>

    <BottomNav v-show="userAgent"></BottomNav>
  </section>
</template>

<script>
import TopNav from './include/TopNav.vue'
import BottomNav from './include/BottomNav.vue'

export default {
  components: {
    TopNav,
    BottomNav
  },
  computed: {
    userAgent: function () {
      // 접속 Agent 모바일/웹 boolean 값
      let mobile = (/iphone|ipad|ipod|android/i.test(navigator.userAgent.toLowerCase()))

      return !mobile
    }
  }
}
</script>

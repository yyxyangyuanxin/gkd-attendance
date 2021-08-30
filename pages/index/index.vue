<template>
  <view class="wrapper">
    <Topbar />
    <Center />
  </view>
</template>

<script>
import Topbar from './topbar.vue'
import Center from './center.vue'
export default {
  components: {
    Topbar,
    Center
  },
  data() {
    return {}
  },
  onLoad() {},
  methods: {},
}
</script>

<style lang="scss" scoped>
</style>

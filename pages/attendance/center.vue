<template>
  <view class="wrapper">
    <view class="atten-btn">
      签到
    </view>
  </view>
</template>

<script>
export default {
  components: {
    
  },
  data() {
    return {}
  },
  onLoad() {},
  methods: {},
}
</script>

<style lang="scss" scoped>
.wrapper{
  position: relative;
  .atten-btn{
    width: 180rpx;
    height: 180rpx;
    line-height: 180rpx;
    text-align: center;
    border-radius: 50%;
    position: absolute;
    top: -90rpx;
    left: 50%;
    transform: translateX(-50%);
    background: #fff;
    box-shadow: 0 0 10rpx 10rpx rgba(0, 0, 0, .1);
    color: #53aefe;
    font-size: 35rpx;
  }
}
</style>
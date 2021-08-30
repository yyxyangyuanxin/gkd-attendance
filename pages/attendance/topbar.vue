<template>
  <view class="wrapper">
    <div class="atten-container">
      <text class="atten-time">
        16:21:56
      </text>
      <text class="atten-date">
        2021年08月30日 星期一
      </text>
    </div>
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
  width: 100%;
  height: 30%;
  position: relative;
  background: linear-gradient(135deg, #0081ff, #40daf2);
  .atten-container{
    position: absolute;
    top: 30%;
    right: 50rpx;
    transform: translateY(-50%);
    display: flex;
    flex-direction: column;
    .atten-time{
      color: #fff;
      font-size: 70rpx;
      letter-spacing: 11rpx;
    }
    .atten-date{
      color: #fff;
      font-size: 32rpx;
      margin-top: 10rpx;
    }
  }
}
</style>
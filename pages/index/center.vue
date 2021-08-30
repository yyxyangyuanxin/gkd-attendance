<template>
  <view class="wrapper">
    <ul class="app-list">
      <li 
        class="app-item"
        v-for="(item, index) in appList"
        :key="index">
        <image class="icon" :src="item.iconUrl" alt="">
        <span>{{ item.name }}</span>
      </li>
    </ul>
  </view>
</template>

<script>
import icon from '@/static/logo.png'
export default {
  data() {
    return {
      appList: [
        {
          iconUrl: icon,
          name: '签到'
        },
        {
          iconUrl: icon,
          name: '公告'
        },
        {
          iconUrl: icon,
          name: '周报'
        },
        {
          iconUrl: icon,
          name: '月报'
        },
        {
          iconUrl: icon,
          name: '总结'
        },
        {
          iconUrl: icon,
          name: '鉴定表'
        },
        {
          iconUrl: icon,
          name: '实习评价'
        },
        {
          iconUrl: icon,
          name: '就业填报'
        },
      ]
    }
  },
  onLoad() {},
  methods: {},
}
</script>

<style lang="scss" scoped>
.wrapper{
  .app-list{
    display: flex;
    flex-wrap: wrap;
    .app-item{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: space-between;
      height: 200rpx;
      padding: 35rpx 0;
      box-sizing: border-box;
      flex: 0 0 25%;
      .icon{
        width: 80rpx;
        height: 80rpx;
        border-radius: 25%;
      }
    }
  }
}
</style>
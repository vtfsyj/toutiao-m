<template>
  <div id="app">
    <h1>今日头条</h1>
    <i class="toutiao toutiao-shipin"></i>
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>

    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
    <div class="box">hello world!!!</div>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped lang="less">
.box {
  width: 200px;
  height: 200px;
  background-color: pink;
}
</style>
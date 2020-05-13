<template>
<div>
      <div class="topnav">
        <a href="https://reactjs.org">叫什么名字呢</a>
        <a href="https://reactjs.org">首页</a>
        <a href="https://reactjs.org">概述</a>
        <a href="https://reactjs.org">位置流量趋势图</a>
        <a href="https://reactjs.org">区域热力图</a>
        <a href="https://reactjs.org">飞线图</a>
        <a href="https://reactjs.org">数据接口</a>
      </div>
    </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
/* 导航条 */
.topnav {
  top: 0;
  left: 0;
  width: 100%;
  position: fixed;
  padding: 10px;
  text-align: center;
  font-weight: bold;
  overflow: hidden;
  background-color: #333;
}

/* 导航链接 */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* 链接 - 修改颜色 */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
</style>

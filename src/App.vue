<template>
  <div v-wechat-title="$route.meta.title" id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
*{margin: 0;padding: 0;}
html{height: 100%;font-family: PingFangSC-Regular}
body{font-size:.28rem;height: 100%;color: #444444;}
div{box-sizing: border-box;}
a{text-decoration: none;}
#app {font-family: 'Avenir', Helvetica, Arial, sans-serif;height: 100%;}
.flex_start{display: flex; justify-content: flex-start;flex-wrap: wrap;}
.flex_center_v{display: flex; justify-content: center;}
.flex_start_v{display: flex; justify-content: flex-start; align-items: center;}
.flex_end{display: flex; justify-content: flex-end;}
.flex_end_v{display: flex; justify-content: flex-end; align-items: center;}
.flex_between{display: flex; justify-content: space-between;}
.flex_between_v{display: flex; justify-content: space-between; align-items: center;}
.flex_around{display: flex; justify-content: space-around;}
.flex_around_v{display: flex; justify-content: space-around; align-items: center;}
.flex_center{display: flex; justify-content: center; align-items: center;}
.vertical_v{display: flex; align-items: center;}
.flex_c{display: flex;flex-direction: column; align-items: center;}
</style>

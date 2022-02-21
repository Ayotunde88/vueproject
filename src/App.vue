<template>
  <div id="overallLeft">
    <LeftComponent/>
  </div>
  <div id="overallRight">
    <RightComponent/>
  </div>
</template>

<script>
import RightComponent from './components/RightComponent.vue'
import LeftComponent from './components/LeftComponent.vue'

export default {
  name: 'App',
  components: {
    RightComponent,
    LeftComponent
  }
}
</script>

<style scoped>
#overallLeft{
  width: 13%;
  float: left;
  position: fixed;
  z-index: 1;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  box-shadow: 4px 0px 16px rgba(16, 30, 115, 0.08);
}
#overallRight{
  width: 85%;
  float: right;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

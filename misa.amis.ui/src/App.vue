<template>
  <div id="app">
    <left-side-bar />
    <Header />
  </div>
</template>
<script>
import Header from './components/common/Header.vue'
import LeftSideBar from './components/common/LeftSideBar.vue'
export default {
  components: { LeftSideBar, Header },
  name:
     'App'
}
</script>
<style >
*{
  margin: 0;
  padding: 0;
}
#app{
  font-family: MISA-Regular ;
  font-size: 13px;
}
@font-face {
  font-family: "MISA-Bold";
  src: url("./assets/fonts/notosans-bold.3ede5aff.woff2");
}
@font-face {
  font-family: "MISA-Regular";
  src: url("./assets/fonts/notosans-regular.2cb88a13.woff2");
}
@font-face {
  font-family: "MISA-Italic";
  src: url("./assets/fonts/notosans-italic.1c1aaac9.woff2");
}
</style>

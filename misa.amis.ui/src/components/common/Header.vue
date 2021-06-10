<template>
  <div class="header-container">
    <div class="three-stripes"></div>
    <div class="header-branch">
      <MSCombobox />
    </div>
    <div class="setting tool">
      <div class="setting-icon"></div>
    </div>
    <div class="help tool">
      <div class="help-icon"></div>
    </div>
    <div class="notification tool">
      <div class="notification-icon"></div>
    </div>
    <div class="user">
      <div class="avatar-user"></div>
      <div class="username">Lưu Văn Đạt</div>
      <div class="info-user"></div>
    </div>
  </div>
</template>
<script>
import MSCombobox from '../combobox/MSCombobox.vue'
export default {
  name: 'Header',
  components: {
    MSCombobox
  }
}
</script>
<style>
.header-container {
  position: absolute;
  left: 178px;
  width: calc(100% - 178px);
  height: 48px;
  display: flex;
}
.three-stripes {
  width: 24px;
  height: 24px;
  margin: 10px;
  background-image: url("../../assets/img/Sprites.64af8f61.svg");
  background-position: -843px -30px;
  background-repeat: no-repeat;
}
.tool {
  height: 100%;
  width: 44px;
  align-items: center;
  display: flex;
  justify-content: center;
}
.notification{
  position: absolute;
  right: calc(30px + 176.19px);
}
.setting{
  position: absolute;
  right: calc(30px + 176.19px + 44px + 44px);
}
.help{
   position: absolute;
  right: calc(30px + 176.19px + 44px);
}
.setting-icon {
  width: 24px;
  height: 24px;
  background-image: url("../../assets/img/Sprites.64af8f61.svg");
  background-position: -675px -30px;
  background-repeat: no-repeat;
}
.help-icon {
  width: 24px;
  height: 24px;
  background-image: url("../../assets/img/Sprites.64af8f61.svg");
  background-position: -731px -30px;
  background-repeat: no-repeat;
}
.notification-icon {
  width: 24px;
  height: 24px;
  background-image: url("../../assets/img/Sprites.64af8f61.svg");
  background-position: -788px -30px;
  background-repeat: no-repeat;
}
.user {
  display: flex;
  height: 36px;
  padding: 6px 0px 0px 0px;
  box-sizing: border-box;
  position: absolute;
  right: 30px;
}
.avatar-user{
  width: 30px;
  height: 30px;
}
.username{
  font-size: 17px;
  padding: 5px 0px;
  font-family: MISA-Semibold;
  color: #111111;
}
.info-user {
  width: 14px;
  height: 14px;
  background-image: url("../../assets/img/Sprites.64af8f61.svg");
  background-position: -1076px -32px;
  background-repeat: no-repeat;
  margin: 10px;
  box-sizing: border-box;
}
</style>

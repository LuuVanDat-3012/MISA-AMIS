<template>
  <div class="menu-container">
    <div class="logo-container">
      <div class="toggle"></div>
      <div class="logo">
        <img
          src="https://actappg1.misacdn.net/img/Logo_Module_TiengViet_White.66947422.svg"
          alt=""
          class="img-icon"
        />
      </div>
    </div>
    <div class="menu">
      <div class="menu-item">
          <div class="menu-item-icon icon-dashboard custom-background"></div>
          <div class="menu-item-text">Tổng quan</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-cash custom-background"></div>
          <div class="menu-item-text">Tiền mặt</div>
      </div>
      <div class="menu-item">
           <div class="menu-item-icon icon-bank custom-background"></div>
          <div class="menu-item-text">Tiền gửi</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-pu custom-background"></div>
          <div class="menu-item-text">Mua hàng</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-sale custom-background"></div>
          <div class="menu-item-text">Bán hàng</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-invoice custom-background"></div>
          <div class="menu-item-text">Quản lý hóa đơn</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-stock custom-background"></div>
          <div class="menu-item-text">Kho</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-tools custom-background"></div>
          <div class="menu-item-text">Công cụ dụng cụ</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-fixed-assets custom-background"></div>
          <div class="menu-item-text">Tài sản cố định</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-tax custom-background"></div>
          <div class="menu-item-text">Thuế</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-price custom-background"></div>
          <div class="menu-item-text">Giá thành </div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-general custom-background"></div>
          <div class="menu-item-text">Tổng hợp</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-budget custom-background"></div>
          <div class="menu-item-text">Ngân sách</div>
      </div>
      <div class="menu-item">
          <div class="menu-item-icon icon-report custom-background"></div>
          <div class="menu-item-text">Báo cáo</div>
      </div>
       <div class="menu-item">
          <div class="menu-item-icon icon-finance custom-background"></div>
          <div class="menu-item-text">Phân tích tài chính</div>
      </div>
    </div>
    <div class="license-info"></div>
  </div>
</template>
<script>
export default {
  name: 'LeftSileBar'
}
</script>
<style>
.menu-container {
  width: 178px;
  height: 100vh;
  position: absolute;
  left: 0;
  box-sizing: border-box;
  background-color: #393A3D;
  box-sizing: border-box;
}
.logo-container {
  height: 48px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.toggle {
  width: 24px;
  height: 24px;
  background-image: url("../../assets/img/Sprites.64af8f61.svg");
  background-repeat: no-repeat;
  background-position: -424px -86px;
  padding-right: 10px;
}
.img-icon {
  width: 96px;
  height: 32px;
  margin-top: 7px;
}
.menu{
   display: flex;
   flex-direction: column;
   height: calc(100vh - 48px);
   padding-top: 10px;
   box-sizing: border-box;
}
.menu-item{
    width: 100%;
    height: 42px;
    display: flex;
    align-items: center;
    padding-left: 16px;
    box-sizing: border-box;
}
.menu-item-icon{
    width: 24px;
    height: 24px;
    min-width: 24px;
    min-height: 24px;
    padding-right: 10px;
}
.menu-item-text{
    color: #fff;
}
.custom-background{
    background-repeat: no-repeat;
}
.icon-dashboard{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -30px -1628px;
}
.icon-cash{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -73px -1628px;
}
.icon-bank{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -117px -1628px;
}
.icon-pu{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -161px -1628px;
}
.icon-sale{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -204px -1628px;
}
.icon-invoice{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -249px -1628px;
}
.icon-stock{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -291px -1628px;
}
.icon-tools{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -336px -1628px;
}
.icon-fixed-assets{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -378px -1628px;
}
.icon-tax{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -423px -1628px;
}
.icon-tax{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -423px -1628px;
}
.icon-price{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -467px -1628px;
}
.icon-general{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -510px -1628px;
}
.icon-budget{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -378px -1659px;
}
.icon-report{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -547px -1628px;
}
.icon-finance{
    background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -204px -1664px
}
.menu-item:hover{
    background-color: #616164;
    cursor: pointer;
}
</style>

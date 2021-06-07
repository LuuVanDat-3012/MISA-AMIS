<template>
    <div class="header-container">
        <div class="three-stripes"></div>
        <div class="header-branch">
                <MSCombobox />
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
.header-container{
    position: absolute;
    left: 178px;
    width: calc(100% - 178px);
    height: 48px;
    display: flex;
}
.three-stripes{
    width: 24px;
    height: 24px;
    margin: 10px;
     background-image: url("../../assets/img/Sprites.64af8f61.svg");
    background-position: -843px -30px;
    background-repeat: no-repeat;
}
</style>

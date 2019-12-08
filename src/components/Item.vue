<template>
  <div>
    <div class = "app-item">
      <div class = "app-list">{{Name}}</div>
        <div class = "app-attribute">{{Attr}}</div> 
    </div>
  </div>
</template>

<script>
export default {
  name: "Item",
  props: {"Name" : {type : String, default: ''}, "Attr" : {type : list, default: ''}}
}
</script>

<style lang = 'less' scoped>
.app-item {
  position: absolute;
  margin-top: 10px;
  display: flex;
  flex-direction: column;
  .app-list {
    margin-top: 0px auto;
    color : #0f0f0f;
  }
  .app-attribute {
    margin-left : 10px;
    margin-top : 0px auto;
    color : #0f0f0f;
  }
}
</style>
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
  props: {"Name" : {type : String, default: ''}, "Attr" : {type : list, default: ''}}
}
</script>

<style lang = 'less' scoped>
.app-item {
  position: absolute;
}
</style>
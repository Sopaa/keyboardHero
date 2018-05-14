<template lang="html">
  <h1 class="footerTitle"> {{ tarbaTitle }}</h1>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      tarbaTitle: 'Dodo'
    }
  }
}
</script>

<style scoped lang="css">
.footerTitle {
  display: table-cell;
  height: 30px;
  position: absolute;
  bottom: 0;

  vertical-align: middle;
  font-size: 20px;
  width: 100vw;
  color: #fff;
  background-color: #686868;
}
</style>

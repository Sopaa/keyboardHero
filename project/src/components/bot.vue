<template lang="html">
  <h2 class="footerTitle"> {{ tarbaTitle }}</h2>
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
  height: 3%;
  position: absolute;
  bottom: 0;
  font-size: 20px;
  width: 100vw;
  color: #fff;
  background-color: #686868;
}
</style>

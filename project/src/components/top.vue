<template lang="html">
  <h1 class="mainTitle"> {{ mainTitle }}</h1>

</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      mainTitle: 'Keyboard Hero made by Dorian & Pierre'
    }
  }
}
</script>

<style scoped lang="css">
.mainTitle {
  display: table-cell;
  height: 100px;
  vertical-align: middle;
  font-size: 20px;
  width: 100vw;
  color: #fff;
  background-color: #686868;
}
</style>

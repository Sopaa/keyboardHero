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
  font-size: 20px;
  color: red;
  background-color: #686868;
}
</style>

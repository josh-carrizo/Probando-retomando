<template>
  <div class="hello col-6">
    <h3>{{ msg }}</h3>
    <div class="row pt-3">
      <div class="col-4">{{ item1 }}</div>
      <div class="col-4">{{ item2 }}</div>
      <div class="col-4">{{ item3 }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Ventas',
  props: {
    msg: String,
    item1: String,
    item2: String,
    item3: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>

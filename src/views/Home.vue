<template>
  <div class="container home text-left">
    <nav aria-label="breadcrumb ">
      <ol class="breadcrumb">
        <li class="breadcrumb-item active" aria-current="page">Home</li>
      </ol>
    </nav>
    <div class="bg-light py-5 text-center">
      Vitrina
    </div>
    <h2>Bienvenidos</h2>
    <p>Bienvenido al sistema de gestión de ventas</p>
    <div class="row">
      <Ventas msg="Estas son las ventas" item1="item1" item2="item2" item3="item3" />
      <Ventas msg="Estas son otras ventas" item1="item1" item2="item2" item3="item3"/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Ventas from '@/components/Ventas.vue'

export default {
  name: 'Home',
  components: {
    Ventas
  }
}
</script>

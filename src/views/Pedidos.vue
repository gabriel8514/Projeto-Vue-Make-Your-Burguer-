<template>
  <div class="main-container">
    <h1>Gerenciar pedidos:</h1>
    <Deshboard/>
  </div>
</template>

<script>
import Deshboard from '../components/Deshboard.vue'

export default {
  name: "Pedidos",
    components: { 
      Deshboard 
    }
}
</script>

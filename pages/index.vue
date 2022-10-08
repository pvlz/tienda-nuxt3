<template>
    <div class="contenedor">
      Hola Mundo
      <br>
      Cuenta {{ cuenta }} 
      <span></span>
      <button @click="incrementar()">+1</button>        
    </div>
</template>

<script>
export default {
  data() {
    return {
      cuenta: 0
    }
  },
  methods: {
    incrementar(){
      this.cuenta++
    }
  },
}
</script>

<style scoped>
.contenedor{
  margin: 25px;
}
span{
  width: 25px;
  display: inline-block;
}
</style>
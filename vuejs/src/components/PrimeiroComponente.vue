<template>
  <div>
    <h1>Olá Pessoal!</h1>
    <p>Meu nome é {{ nome }}</p>
  </div>
</template>

<script>
export default {
  name: 'PrimeiroComponente',
  data() {
    return {
      nome: "Armando",
      
    }
  }
}
</script>
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Calculadora />
</template>

<script>
import Calculadora from "@/components/Calculadora.vue";

export default {
  name: 'App',
  components: {
    Calculadora
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
}
</style>

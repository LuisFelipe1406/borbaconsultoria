<script setup lang="ts">

</script>

<template>
  <div id="divMain">
    
  </div>
</template>

<style scoped>
  #divMain {
    background-image: url('/img/main.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;

    height: 100vh;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  /* Alteramos o espaçamento dos elementos de acordo com o tamanho da tela */
  @media only screen and (max-width: 1200px) {
    #divMain {
      background-image: url('/img/main-mobile.png');
    }
  }

</style>
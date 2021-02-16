<template>
  <div>
    <h1 :style="{ textDecoration: decoration }">Hello {{ name }}!</h1>
    <br>
    <input type="text" v-model="name">
    <br>
    <a :href="link">Link pro curso!</a>
  </div>
</template>

<script>
export default {
  data: () => ({
    name: 'Rudys',
    link: 'https://treinamento.vuejsbrasil.org',
    decoration: 'underline'
  })
}
</script>

<style>
    div{
        margin: 0;
        padding: 0;
        width: 100%;

        display: flex;
        justify-content: center;
        align-content: center;
    }
    
</style>
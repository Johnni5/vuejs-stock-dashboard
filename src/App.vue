<template>

    <Card>
      <h1>Mein Titel</h1>
      <p>Ein paar Details hier.</p>
    </Card>

</template>

<script>
import Card from './components/Card.vue';

export default {

  name: 'stock-Dashboard',
  components: {
    Card,
  }
}
</script>

<style>
  body {
    margin: 0;
    /* padding: 0;  */
  }

  #app {
    width: 100vw;
    min-height: 100vh;
    padding: 100px;
    background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%20%);
    box-sizing: border-box;
    font-family: 'Rubik', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /* margin-top: 60px; */
  }
</style>

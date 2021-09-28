<template>
  <div class="container">
    <Header />

  </div>

</template>

<script>
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    Header

  }
}
</script> 

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Display:wght@100&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  /* background-color: 774040; */
  font-family: 'Noto Sans Display', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #774040;
}

.container {
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid #2c3e50;
  padding: 30px;
  border-radius: 50;
  background-color: #470000;
  color: whitesmoke;
  
  
}
</style>

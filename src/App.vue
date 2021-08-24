<template>
  <div id="app">
    <h1>Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from './main/Calculator'

export default {
  components: {Calculator}
}
</script>

<style>
@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-VariableFont_wght.ttf");
}

*{
  font-family: 'RobotoMono', monospace;
}

body{
  margin: 0;
}

#app{
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  background: linear-gradient(90deg, rgba(43,23,110,1) 10%, rgba(144,118,233,1) 90%);
}
</style>
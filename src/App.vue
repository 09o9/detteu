<template>
  <div class="main">
  <img alt="Vue logo" src="./assets/what-is-coding-1.jpg">
  <h1>Hello, World!</h1>
  
 <p>취미로 코딩하는 데뜨(Detteu)입니다.</p>

</div>

<div class="stack">
   <ul>
    <h2>Stack 🥏</h2>
    <li>HTML</li>
    <li>CSS</li>
    <li>JAVASCRIPT</li>
    <li>VUE.JS</li>
   </ul>
  </div>
 <br> <br>
  <div class="stack">
   <ul>
    <h2>DSICORD 🥏</h2>
    <li>USER ID: _detteu</li>
    <li>COMMUNITY: <a href="https://discord.gg/a9wpx5YjYC">https://discord.gg/a9wpx5YjYC</a></li>
    
   </ul>
  </div>

 
</template>

<script>


export default {
  name: 'App',
  components: {
  
  }
}
</script>

<style>

body {
  color: white;
  background-color: #2c3e50;
}
#app {
 
 
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
  
}

.main {
  width: 100%;
  height: 100vh;
}
.main img {
  border-radius: 20px;
  height: 300px;
  width: 100%;
}

.main h1 {
  font: 5em sans-serif;
  text-shadow: 2px 2px 4px rgba(49, 64, 202, 0.637); /* 수평 오프셋, 수직 오프셋, 흐림 정도, 그림자 색상 */
}

.stack {
  
  text-align: left;
  color: #2c3e50;
  border-radius: 5px;
  height: 500px;
  background-color: aliceblue;
  width: 100%;
}

.stack h2 {
  text-decoration: underline;
  font-size: 50px;
}
.stack ul {
  font-size: 25px;
  margin-left: 30px;
}


</style>

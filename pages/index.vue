<template>
  <div>

    <header>
    <nav>
      <div class="logo"><h3>PlanetVirtron</h3></div>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#roadmap">Road Map</a>
        <a href="#contact">Contact</a>
      </div>
      <div>
        <a href="#login">Login</a>
        <a href="#join"><button>Join</button></a>
      </div>
    </nav>
    <main>
      <div class="container">
        <div class="box1">
          <img src="img/(1-0-0) Wilson-vs-Shaw.jpg" alt="">
          <h2>This is my example.</h2>
          <p>This is how it will look</p>
          <input type="text">
          <a href="#nowhere">Link to Nowhere</a>
        </div>
        <div class="box1">
          <img src="img/(2-0-0) Wilson-vs-Terry.jpg" alt="">
          <h2>This is my example.</h2>
          <p>This is how it will look</p>
          <a href="#nowhere">Link to Nowhere</a>
        </div>
        <div class="box1">
          <h2>This is my example.</h2>
          <p>This is how it will look</p>
          <a href="#nowhere">Link to Nowhere</a>
        </div>
      </div>
      <div class="container">
        <div class="box2">
          <h2>This is my example 2.</h2>
          <p>This is how it will look</p>
          <a href="#nowhere">Link to Nowhere</a>
        </div>
      </div>
    </main>
  </header>

  </div>
</template>

<script setup>

</script>

<style coped>
  * {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color:lightslategray;
}

header {
  position: absolute;
  width: 100%;

}

nav {
  position: relative;
  position: fixed;
  width: 100%;
  height: 50px;
  background-color: rgba(211, 211, 211, 0.94);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 30px;
}

.nav-links a {
  padding: 0 6px;
}

main {
margin-top: 50px;
}

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  width: 90%;
  margin: auto;
}

button {
  width: 60px;
  height: 25px;
  background-color: rgb(87, 149, 220);
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}

button:hover {
  background-color: rgb(75, 130, 194);
  transition-delay: 6ms
}

.box1 {
  width: 400px;
  height: 400px;
  background-color: lightgray;
  margin-top: 60px;
}

.box2 {
  width: 1000px;
  height: 400px;
  background-color: lightgray;
  margin-top: 60px;
}

img {
  width: 400px;
}
</style>
<template>
  <div id="container" class="div-position flex-column py-5">
    <p class="mx-5"><a href=""> VERONA </a></p>
    <p class="mx-5"><a href=""> OPEN </a></p>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Monoton&display=swap');

.div-position {
  position: absolute;
  right: 1%;
  top: 48%;
}

#container {
  width: 100%;
  margin: auto;
}

/*Neon*/
p {
  font-family: 'Monoton', cursive;
  text-align: center;
  font-size: 1.5em;
  margin: 0px 0 0px 0;
}

a {
  font-family: 'Monoton', cursive;
  text-decoration: none;
  -webkit-transition: all 0.5s;
  -moz-transition: all 0.5s;
  transition: all 0.5s;
}

p:nth-child(1) a {
  font-family: 'Monoton', cursive;
  font-size: 1.5em;
  color: #fff;
  -webkit-animation: neon1 1.5s ease-in-out infinite alternate;
  -moz-animation: neon1 1.5s ease-in-out infinite alternate;
  animation: neon1 1.5s ease-in-out infinite alternate;
}

p:nth-child(1) a:hover {
  color: #ff1177;
  -webkit-animation: none;
  -moz-animation: none;
  animation: none;
}

p:nth-child(2) a {
  font-family: 'Monoton', cursive;
  font-size: 1.5em;
  color: #228dff;
  -webkit-animation: neon1 1.5s ease-in-out infinite alternate;
  -moz-animation: neon1 1.5s ease-in-out infinite alternate;
  animation: neon1 1.5s ease-in-out infinite alternate;
}

p:nth-child(2) a:hover {
  color: #228dff;
  -webkit-animation: none;
  -moz-animation: none;
  animation: none;
}

p a:hover {
  color: #ffffff;
}
/*glow for webkit*/

@-webkit-keyframes neon1 {
  from {
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #ffffff,
      0 0 30px #ffffff, 0 0 40px #ffffff, 0 0 60px #ffffff, 0 0 80px #ffffff;
  }
  to {
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #fff, 0 0 20px #ff1177,
      0 0 35px #2600fd, 0 0 40px #ff1177, 0 0 50px #ff1177, 0 0 75px #2600fd;
  }
}

/*glow for mozilla*/

@-moz-keyframes neon1 {
  from {
    text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #ff1177,
      0 0 70px #ff1177, 0 0 80px #ff1177, 0 0 100px #ff1177, 0 0 150px #ff1177;
  }
  to {
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #fff, 0 0 20px #ff1177,
      0 0 35px #ff1177, 0 0 40px #ff1177, 0 0 50px #ff1177, 0 0 75px #ff1177;
  }
}

@media (max-width: 960px) {
  #container {
    width: 100%;
    margin: 0 !important;
  }
  p {
    font-size: 10px;
  }

  .div-position {
    position: absolute;
    right: 1%;
    top: 38%;
  }
}
</style>

<script >
export default {
  data() {
    return {
      count: "Chaya"
    }
  }
}
</script>

<template>
  <header>
    <div class="container">
      <h1 class="text-center my-2 h1">{{ count }} Segal-Full stack Projects</h1>
      <hr />
    </div>
  </header>

  <main>
    <div class="d-flex flex-wrap justify-content-center text-center container">

      <div class="maimDiv">
        <p class="text-center">Social Network that help keep healthy lifestyle-end to end project</p>
        <a target="_blank" href="https://healthy-me1.netlify.app">
          <img class="img" src="/images/health2.gif" alt="breakFast" width="500">
        </a>
      </div>

      <div class="maimDiv">
        <p class="text-center">Restaurant website. Pure code in HTML, CSS, JavaScript-Pure code</p>
        <a target="_blank" href="https://breakfastchaya.netlify.app">
          <img class="img" src="/images/breakFast.gif" alt="breakFast" width="500">
        </a>
      </div>

      <div class="maimDiv">
        <p class="text-center">Atlas -countries in the world! Search any country you want</p>
        <a target="_blank" href="https://atlascountry.netlify.app/">
          <img class="img" src="/images/atlas2.gif" alt="atlas" width="500">
        </a>
      </div>

      <div class="maimDiv">
        <p class="text-center">A shopping list application - using: React, Ridex and LocalStorage</p>
        <a target="_blank" href="https://my-shopping-lists.netlify.app/">
          <img class="img" src="/images/shop2.gif" alt="shopping" width="500">
        </a>
      </div>

      <div class="maimDiv">
        <p class="text-center">Check the weather of any country/city you want</p>
        <a target="_blank" href="https://which-weather.netlify.app/">
          <img class="img" src="/images/weather2.gif" alt="weather" width="500">
        </a>
      </div>

      <div class="maimDiv">
        <p class="text-center">Api of clothes- technologies: NodeJS, MongoDb, Postman, express.js</p>
        <a target="_blank" href="https://apiclothes.cyclic.app/">
          <img class="img" src="/images/api.gif" alt="apiClothes" width="500">
        </a>
      </div>

    </div>
  </main>

  <footer>
    <div class="container py-4">
      <div class="row align-items-center justify-content-center">

        <div class="d-flex align-items-center mx-auto justify-content-center me-md-5 ">
          <h5>Learned in BlackOps college</h5>
          <img class="col-2 col-md-1" src="/images/scores.jpeg" alt="breakFast" >
        </div>

        <div class="d-flex justify-content-around justify-content-md-center mt-5">

          <h1 class="display-1 mx-md-5 ">
            <a class="pink" target="_blank" href="https://github.com/chayale90">
              <i class="fa fa-github" aria-hidden="true"></i>
            </a>
          </h1>

          <h1 class="display-1 mx-md-5">
            <a target="_blank" href="https://www.linkedin.com/in/chaya-segal/">
              <i class="fa fa-linkedin-square" aria-hidden="true"></i>

            </a>
          </h1>

          <h1 class="display-1 mx-md-5">
            <a target="_blank" class="black" href="tel:055-6649380" type="tel">
              <i class="fa fa-phone-square" aria-hidden="true"></i>
            </a>
          </h1>

          <h1 class="display-1 mx-md-5">
            <a target="_blank" class="green" href="https://api.whatsapp.com/send?phone=0556649380" type="whatsapp">
              <i class="fa fa-whatsapp" aria-hidden="true"></i>
            </a>
          </h1>

        </div>
      </div>
    </div>
  </footer>
  <RouterView />
</template>


<style>
body {
  font-family: 'Arima', cursive;
  font-family: 'Roboto', sans-serif;
  overflow-x: hidden;
}

.img {
  border: 2px solid pink;
  border-radius: 10px 10px;
  width: 500px;
}

.pink {
  color: rgb(219, 103, 122)
}
.pink:hover {
  color: rgb(175, 87, 101)
}

.black {
  color: rgb(10, 7, 8)
}
.black:hover {
  color: rgb(95, 86, 89)
}

.green {
  color: rgb(38, 171, 31)
}
.green:hover {
  color: rgb(24, 105, 19)
}

.h1 {
  color: rgb(219, 103, 122)
}

.maimDiv {
  width: 500px;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 20px 10px;
}



@media (max-width:768px) {
  .maimDiv {
  width: 100%;
}
.img {
  width: 350px;
}
}

</style>

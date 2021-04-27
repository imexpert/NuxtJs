<template>
  <section class="container">
    <h1 class="title">Ana Sayfa</h1>
    <p class="subtitle">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate aperiam eaque rem ullam? Blanditiis, omnis! Architecto, amet facilis ad sequi earum ipsa, animi labore quas modi consequatur delectus voluptatum harum!
    </p>

    
    <div class="button container">
      <a href="/products" class="button--green">Ürünler (Server Side)</a>
      <a href="#" class="button--green">Ürünler</a>
      <nuxt-link to="/products/1" tag="a" class="button--green">Ürünler</nuxt-link>
    </div>
  </section> 
</template>



<style>
.container {
  margin-top:50px;
  min-height: 100vh;
  align-items: center;
  text-align: center;
}
.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

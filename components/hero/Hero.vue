<template>
  <div class="hero is-medium is-bold">
    <div class="body">
      <div class="container">
      <div class="logo">
        <img
       class="img"
       src="../../static/logo.png">
      </div>
      <div class="center">
        <h1 class="title">
          AL KASBAH CHICHA PAS CHER : TOUS NOS NARGUILÉS À PETITS PRIX
        </h1>
        <h5 class="subtitle">
          S’adaptant aux budgets les plus réduits, Al Kasbah propose une
          collection de chichas et d’accessoires à petits prix. Vous trouverez
          ici l’ensemble de nos chichas pas chères vendues à moins de 100€ afin
          de vous faire plaisir, le tout à petit prix.
        </h5>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style lang="scss" scoped>

.hero {
  margin: 20px;
  padding: 0px;
}
.body {
  display: flex;
  padding: 0px;
}
.center {
  text-align-last: center;
}
.container {
  background-color: white;
  border: 3px solid grey;
  padding: 10px;
  box-sizing: content-box;

}
h5 {
  color: grey;
  font-size: 14px;
}
h1 {
  color: black;
  font-size: 24px;
}
.img {
  border-radius: 50%;
  width: 15%;
  }
  .logo {
        text-align-last: center;
  }
</style>

<template>
  <section class="section has-navbar-fixed-top">
    <div class="container">
      <div class="columns is-mobile is-centered">      
        <div class="column is-narrow">
          <h1 class="background-black">Anna Gallo</h1>
        </div>
      </div>
      <div class="container">
        <div class="columns is-mobile is-centered">
          <div class="column is-narrow">
            <h3 class="background-green">UX Developer</h3>
          </div>
        </div>
      </div>
      <div class="container wrapper">
        <div class="columns is-centered">
          <div class="column is-narrow">
            <img class="img-round" src="../assets/img/headshot.jpg" alt="Anna's Headshot" width="200px" height="200px">
          </div>
        </div>
      </div>
      </div>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: "Anna Gallo | About"
    };
  }
};
</script>

<style lang="scss">
@import "~assets/css/main.scss";
.background-black {
  background-color: $black;
  color: $white;
  text-align: center;
  margin-top: 4rem;
  font-size: 2.5rem;
  padding: 0 1rem;
  @media screen and (min-width: $tablet) {
    font-size: 4rem;
    padding: 0 3rem;
  }
}
.background-green {
  background-color: $green;
  color: $white;
  text-align: center;
  font-size: 1.25rem;
  padding: 0 1rem;
  margin-bottom: 2rem;
  @media screen and (min-width: $tablet) {
    font-size: 1.75rem;
    padding: 0 3rem;
  }
}
.img-round {
  border-radius: 50%;
  border: 10px solid $green;
    @media screen and (max-width: $tablet) {
    width: 50%;
  }
}
</style>

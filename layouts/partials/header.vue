<template>
  <section class="section">
    <div class="container">
      <div class="columns is-mobile is-centered">
        <div class="column is-narrow has-text-centered">
          <img
            class="img-round"
            src="../../assets/img/headshot.jpg"
            alt="Anna's Headshot"
            width="150"
            height="150"
          />
        </div>
      </div>
      <div class="columns is-mobile is-centered">
        <div class="column is-narrow">
          <h1 class="background-black">Anna Gallo</h1>
        </div>
      </div>
      <div class="container">
        <div class="columns is-mobile is-centered">
          <div class="column is-narrow">
            <h3 class="background-green">Designer + Developer</h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "~assets/css/main.scss";
.background-black {
  background-color: $black;
  color: $white;
  text-align: center;
  margin-top: 2rem;
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
  margin-bottom: 2.5rem;
  @media screen and (min-width: $tablet) {
    font-size: 1.5rem;
    padding: 0 3rem;
  }
    @media screen and (max-width: $tablet) {
margin-bottom: 0;
  }
}
.img-round {
  border-radius: 50%;
  border: 5px solid $green;
}
</style>
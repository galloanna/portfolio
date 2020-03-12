<template>
  <section class="section">
      <div class="container">
        <div class="columns top-row is-mobile is-centered">
          <div class="column is-narrow has-text-centered" data-aos="fade"
            data-aos-duration="1500"
            data-aos-offset="0"
            data-aos-delay="0">
              <a class="top-link" href="https://www.linkedin.com/in/annargallo" target="_blank">linkedin</a><a class="top-link" href="https://drive.google.com/file/d/1PeymxoL2An5Fn8anOjunmTTlIXVN5pB6/view?usp=sharing" target="_blank">resume</a><a class="top-link" href="mailto:heyannagallo@gmail.com">heyannagallo@gmail.com</a>
          </div>

        </div>
      </div>
    <div class="container">
      <div class="columns is-mobile is-centered">
        <div class="column is-narrow has-text-centered">
          <img
            class="img-round"
            src="../../assets/img/headshot.jpg"
            alt="Anna's Headshot"
            width="150"
            height="150"
            data-aos="fade"
            data-aos-duration="1500"
            data-aos-offset="0"
            data-aos-delay="500"
          />
        </div>
      </div>
      <div class="columns is-mobile is-centered">
        <div class="column is-narrow">
          <h1
            class="background-black"
            data-aos="fade"
            data-aos-duration="1500"
            data-aos-offset="0"
            data-aos-delay="1000"
          >Anna Gallo</h1>
        </div>
      </div>
      <div class="container">
        <div class="columns is-mobile is-centered">
          <div class="column is-narrow">
            <h3
              class="background-green"
              data-aos="fade"
              data-aos-duration="1500"
              data-aos-offset="0"
              data-aos-delay="1500"
            >UX Developer</h3>
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
.top-row {
  & a {
    text-decoration: underline;
    padding: 0 1rem;
  }
}
</style>
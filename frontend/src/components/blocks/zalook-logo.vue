<template>
  <div class="logo-container">
    <div class="logo">
      <img src="../../assets/images/Rayhans Fashion.png" alt />
    </div>
    <h1 class="Rayhans Fashion-logo">Rayhans Fashion</h1>
  </div>
</template>

<script>
export default {
  name: 'Rayhans FashionLogo',
}
</script>

<style lang="scss" scoped>
.logo-container {
  padding: 1.5em 0;
  display: flex;
  align-items: center;

  .logo {
    width: 2em;
    margin-right: 0.7em;
  }

  img {
    max-width: 100%;
    transform: rotate(-30deg);
  }

  h1 {
    font-weight: 400;
    font-size: 1.5rem;
    position: relative;
  }

  @media only screen and (min-width: 768px) {
    padding-top: 3em;
    padding-bottom: 0;

    h1 {
      font-size: 2.25em;
    }
  }
}
</style>

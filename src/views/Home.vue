<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <BurgerForm />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import BurgerForm from '../components/BurgerForm.vue'
export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm
  }
}
</script>

<style scoped>
  h1 {
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: red;
    font-style: italic;
  }
</style>



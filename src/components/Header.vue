<template>
  <header>
    <div class="container">
      <Logo />
      <Navbar />
    </div>
  </header>
</template>

<script>
import Logo from './barra_header/Logo.vue';
import Navbar from './barra_header/Navbar';


export default {
    name: 'Header',
    components: {
        Logo,
        Navbar,
      }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';

.container {
  height: 120px;
}

</style>
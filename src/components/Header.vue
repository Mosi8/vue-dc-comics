<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <nav>
        <ul>
          <li v-for="(element, index) in links" :key="index">
            <a href="#" :class="{'active': element.current}">{{element.text}}</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
      return{
        links: [
            {
                text: "Home",
                url: "#",
                current: false,
            },
            {
                text: "Prodotti",
                url: "#",
                current: true,
            },
            {
                text: "Chi Siamo",
                url: "#",
                current: false,
            },
            {
                text: "Contatti",
                url: "#",
                current: false,
            },
        ]
      }
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';


header{
  text-align: center;
}
nav{

  ul{
    list-style-type: none;
    display: flex;
    justify-content: center;

    li a{
      display: inline-block;
      color: #000;
      padding: 15px 20px;
      text-decoration: none;
   
      // nav ul li a.active, nav ul li a:hover 
      &.active, &:hover{
        background-color: $secondaryColor;
      }

    }
  }

}
</style>
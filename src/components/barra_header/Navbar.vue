<template>
    <nav>
        <ul>
          <li v-for="(element, index) in links" :key="index">
            <a href="#" :class="{'active': element.current}">{{element.text}}</a>
          </li>
        </ul>
      </nav>
</template>

<script>
export default {
    name: 'Navbar',
    data() {
      return{
        links: [
            {
                text: "CHARACTERS",
                url: "#",
                current: false,
            },
            {
                text: "COMICS",
                url: "#",
                current: true,
            },
            {
                text: "MOVIES",
                url: "#",
                current: false,
            },
            {
                text: "TV",
                url: "#",
                current: false,
            },
            {
                text: "GAMES",
                url: "#",
                current: false,
            },
            {
                text: "COLLECTIBLES",
                url: "#",
                current: false,
            },
            {
                text: "VIDEOS",
                url: "#",
                current: false,
            },
            {
                text: "FANS",
                url: "#",
                current: false,
            },
            {
                text: "NEWS",
                url: "#",
                current: false,
            },
            {
                text: "SHOP",
                url: "#",
                current: false,
            },
        ]
      }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

nav{
  float: right;
  font-size: 12px;
  line-height: 120px;
  vertical-align: middle;
  
  ul{
    list-style-type: none;
    display: flex;
    justify-content: center;

    li a{
      display: inline-block;
      color: #000;
      margin: 0 15px;
      text-decoration: none;
   
      // nav ul li a.active, nav ul li a:hover 
      &.active, &:hover{
        border-bottom: solid 4px rgb(73, 129, 245);
      }

    }
  }

}
</style>
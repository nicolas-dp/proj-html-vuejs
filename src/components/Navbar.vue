<template>
  <li class="nav-item">
    <a class="nav-link active" href="#">{{ link }}</a>
  </li>
</template>

<script>
export default {
  name: "NavBar",
  props: {
    link: Array,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
nav {
  
  font-size: 10px;
  li {
      padding: 0.5rem;
      
  }

  .nav-item>a{
      color: white;
  }
}
</style>
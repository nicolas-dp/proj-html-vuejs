<template>
  <li class="nav-item ">
    <a class="nav-link active" :href="'#'+link.text"
      >{{ link.text }}
      <span v-if="link.icon"
        ><font-awesome-icon icon="fa-solid fa-cart-shopping"
      /></span>
      <span class="btn-new" v-if="link.text == 'Takeout'">New</span>
    </a>
  </li>
</template>

<script>
export default {
  name: "NavBar",
  props: {
    link: Object,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.nav-item > a {
  color: var(--small-textColor);

}

li:hover a{
  color: white!important;
}

.btn-new {
  border: 1px solid var(--small-textColor);
  font-size: 10px;
  padding: 0.3rem;
  vertical-align: text-bottom;
}
</style>
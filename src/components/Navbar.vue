<template>
    <nav>
        <a href="#">{{link}}</a>
    </nav>
</template>

<script>
export default {
  name: 'NavBar',
    props:{
        link: Array
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
 
</style>
<template>
  <footer>
    <div class="copy">
      <small class="text-white"
        >Copyright 2022 Avada | All Rights Reserved | Powered by
        <strong>Boolean</strong> | Nicolas De Palma</small
      >
    </div>
  </footer>
</template>

<script>
export default {
  name: "CopyRight",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.copy {
  background-color: black;
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;

  small {
    font-size: 10px;
  }
}
</style>
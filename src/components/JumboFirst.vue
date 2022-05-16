<template>
  <div class="jumbo_text container mt-5 mb-5">
    <div class="col-4">
      <div class="title_small">
        <div class="text_best"></div>
        <small>THE BEST TABLE IN TOWN</small>
      </div>
      <div class="main_text p-5">
        <h1 class="fw-bold fs-1">FINE DINING EXPERIENCE</h1>
        <p calss="fw-light p-3">
          Pallentesque vitae viverra risus, sagittis. Venenatis ridiculus
          scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
        </p>
        <a href="#" class="btn_dark"><small>EXPLORE THE MENU</small></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "JumboFirst",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.jumbo_text {
  color: white;
}


.text_best {
  border-top: 1px solid var(--small-textColor);
  width: 23px;
  height: 5px;
  margin-right: 2rem;
  display: inline-block;
}


.col-4 {
  small,
  p {
    color: var(--small-textColor);
  }
}

.btn_dark {
  border: 1px solid var(--small-textColor);
  font-size: 13px;
  padding: 0.5rem;
  text-decoration: none;
  
  &:hover {
  background-color: white;
  color: black;
}
}
</style>
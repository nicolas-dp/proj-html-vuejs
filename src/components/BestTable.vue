<template>
  <section id="the_best_table">
    <div class="row flex-nowrap mt-5" style="height: 750px">
      <div class="col-8 col_bg"></div>
      <div class="col col_dark text-white">
        <div class="title_small">
          <div class="text_best"></div>
          <small>THE BEST TABLE IN TOWN</small>
        </div>
        <div class="main_text p-5">
          <h2 class="fw-bold fs-1">FINE DINING EXPERIENCE</h2>
          <p calss="fw-light p-3">
            Pallentesque vitae viverra risus, sagittis. Venenatis ridiculus
            scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
          </p>
          <a href="#" class="btn_dark"><small>EXPLORE THE MENU</small></a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "BestTable",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>



.col_bg {
  background-image: url("@/assets/img/slider32x.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}



.title_small{
  margin-top: 4rem;
}


</style>
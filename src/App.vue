<template>
  <div id="app">
    <SiteHeader />
    <HeroRoll />
    <BestTable />
    <section id="critics">
      <div class="container">
        <h3 class="fst-italic text-center">What critics are saying about us</h3>
        <div class="text_best"></div>
        <div class="row">
          <div class="col-6 p-0">
            <img class="img-fluid" src="@/assets/img/blog72x.jpg" alt="..." />
          </div>
          <div class="col-6 col_dark">
            <div class="title_small">
              
              <small>MEGGY STEWART</small>
            </div>
            <div class="main_text p-5">
              <h2 class="fw-bold fs-1">NEW YORK TIMES</h2>

              <div class="text_best"></div>
              <p calss="fw-light p-3">
                Pallentesque vitae viverra risus, sagittis. Venenatis ridiculus
                scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
              </p>
              <p calss="fw-light p-3">
                Sit tempor a et nisl, ac felis.Venenatis ridiculus
                scelerisque nisi in urna nulla.
              </p>
              <a href="#" class="btn_dark"><small>READ FULL ARTICLE</small></a>
            </div>
          </div>
          <div class="col"></div>
          <div class="col"></div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import SiteHeader from "@/components/SiteHeader.vue";
import HeroRoll from "@/components/HeroRoll.vue";
import BestTable from "@/components/BestTable.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    HeroRoll,
    BestTable,
  },
};
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";

#critics .text_best{
  width: 50px;
}
</style>

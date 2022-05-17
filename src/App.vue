<template>
  <div id="app">
    <SiteHeader />
    <HeroRoll />
    <BestTable />
    <section id="critics">
      <div class="container">
        <h3 class="fst-italic text-center">What critics are saying about us</h3>
        <div class="text_best" style="left: 48%; position: relative"></div>
        <div class="row justify-content-center">
          <div class="col-5 p-0">
            <img class="img-fluid" src="@/assets/img/blog72x.jpg" alt="..." />
          </div>
          <div class="col-5 col_dark">
            <div class="title_small">
              <small>MEGGY STEWART</small>
            </div>
            <div class="main_text">
              <h3 class="fw-bold">NEW YORK TIMES</h3>
              <div class="star">
                <font-awesome-icon
                  icon="fa-solid fa-star"
                  v-for="i in 5"
                  :key="i"
                  class="p-1"
                />
              </div>
              <div class="text_best"></div>
              <p calss="fw-light">
                Pallentesque vitae viverra risus, sagittis. Venenatis ridiculus
                scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
              </p>
              <p calss="fw-light">
                Sit tempor a et nisl, ac felis.Venenatis ridiculus scelerisque
                nisi in urna nulla.
              </p>
              <a href="#" class="btn_dark"><small>READ FULL ARTICLE</small></a>
            </div>
          </div>
          <!-- The guardian -->
          <div class="col-5">
            <div class="card_critics">
              <img class="img-fluid" src="@/assets/img/info52x.jpg" alt="..." />
              <div class="text_hover">
                <div class="title_small">
                  <small>MARY MAXEY</small>
                </div>
                <div class="main_text">
                  <h3 class="fw-bold">THE GUARDIAN</h3>
                  <div class="star">
                    <font-awesome-icon
                      icon="fa-solid fa-star"
                      v-for="i in 5"
                      :key="i"
                      class="p-1"
                    />
                  </div>
                  <div class="text_best"></div>
                  <p calss="fw-light">
                    Non arcu mauris tortor ultriees mollis tellus euismod
                    fermentum. Habitant amet tineidunt id sapien accumsan sed.
                  </p>
                  <a href="#" class="btn_dark"
                    ><small>READ FULL ARTICLE</small></a
                  >
                </div>
              </div>
            </div>
          </div>
          <!-- Globe and mail -->
          <div class="col-5">
            <div class="card_critics">
              <img class="img-fluid" src="@/assets/img/info12x.jpg" alt="..." />
              <div class="text_hover">
                <div class="title_small">
                  <small>PATRICK MONROE</small>
                </div>
                <div class="main_text">
                  <h3 class="fw-bold">GLOBE AND MAIL</h3>
                  <div class="star">
                    <font-awesome-icon
                      icon="fa-solid fa-star"
                      v-for="i in 5"
                      :key="i"
                      class="p-1"
                    />
                  </div>
                  <div class="text_best"></div>
                  <p calss="fw-light">
                    Vivamus magna justo, lacinia eget conseetetur sed, convallis
                    at tellus. Nulla porttitor accumsan tincidunt.
                  </p>
                  <a href="#" class="btn_dark"
                    ><small>READ FULL ARTICLE</small></a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="kung_pao">
      <div class="middle_jumbo">
        <span class="fw-bold text-white">KUNG PAO CHICKEN - $32</span>
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

#critics .text_best {
  width: 50px;
}

#critics {
  a > small {
    font-size: 10px;
  }
}

.card_critics {
  position: relative;
}

.text_hover {
  box-shadow: inset 0 166px 97px 20px #000000cf;
  position: absolute;
  top: 0;
  bottom: 0;
  padding: 5rem;
  background-color: #00000082;
}

.middle_jumbo {
  position: relative;
  margin-top: 4rem;
  background-image: url("@/assets/img/page52x.jpg");
  height: 100vh;
  background-repeat: no-repeat;
  background-size: contain;
}

.middle_jumbo span {
  position: absolute;
  bottom: 2rem;
  left: 45%;
  filter: drop-shadow(2px 4px 6px black);
}
</style>

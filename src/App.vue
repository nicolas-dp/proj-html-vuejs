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

    <section id="promotions">
      <div class="container">
        <h3 class="fst-italic text-center">Latest news E promotions</h3>
        <div class="text_best" style="left: 48%; position: relative"></div>
        <div class="card-group">
          <div class="card">
            <img
              src="@/assets/img/blog92x-1200x1375.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">THE BEST COFFEE IN TOWN</h5>
              <p class="card-text">
                <small class="text-muted"
                  >By admin | January 7th, 2020 | Categories News</small
                >
              </p>
            </div>
          </div>
          <div class="card">
            <img
              src="@/assets/img/blog72x-1200x1375.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">DISCOVER OUR NEW MENU</h5>
              <p class="card-text">
                <small class="text-muted"
                  >By admin | January 7th, 2020 | Categories News</small
                >
              </p>
            </div>
          </div>
          <div class="card">
            <img
              src="@/assets/img/blog82x-1200x1375.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">WE NOW ACCEPT SQUARE!</h5>
              <p class="card-text">
                <small class="text-muted"
                  >By admin | January 7th, 2020 | Categories News</small
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="takeout">
      <div class="row flex-nowrap mt-5" style="height: 750px">
        <div class="col-8 col_bg"></div>
        <div class="col col_dark text-white">
          <div class="title_small">
            <div class="text_best"></div>
            <small>ENJOY YOUR MEAL AT HOME</small>
          </div>
          <div class="main_text p-5">
            <h2 class="fw-bold fs-1">TAKEOUT NOW AVAILABLE</h2>
            <p calss="fw-light p-3">
              Pallentesque vitae viverra risus, sagittis. Venenatis ridiculus
              scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
            </p>
            <a href="#" class="btn_dark"
              ><small
                ><font-awesome-icon
                  class="pe-1"
                  icon="fa-solid fa-car-side"
                />VIEW TAKE OUT MENU</small
              ></a
            >
          </div>
        </div>
      </div>
    </section>

    <section id="menu">
      <div class="container">
        <div class="row">
          <div class="col bg_gray">
            <h4 class="fw-bold p-4">HORS D'OEUVRES</h4>
            <ul v-for="(menu, index) in menu_hors" :key="index">
              <li>
                <h6>{{ menu.title }}</h6>
                <span>$ {{ menu.price }}</span>
                <p>{{ menu.description }}</p>
              </li>
            </ul>
          </div>
          <div class="col bg_main_menu">
            <h4 class="fw-bold">MAIN COURSE</h4>
            <ul v-for="(menu, index) in menu_main" :key="index">
              <li>
                <h6 class="fw-bold">{{ menu.title }}</h6>
                <span>$ {{ menu.price }}</span>
                <p>{{ menu.description }}</p>
              </li>
            </ul>
          </div>
          <div class="col bg_gray">
            <h4 class="fw-bold">DESSERT</h4>
            <ul v-for="(menu, index) in menu_dessert" :key="index">
              <li>
                <h6>{{ menu.title }}</h6>
                <span>$ {{ menu.price }}</span>
                <p>{{ menu.description }}</p>
              </li>
            </ul>
          </div>
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

  data() {
    return {
      menu_hors: [
        {
          title: "AHI SALMON NIGIRI",
          price: 44,
          description:
            "Eget vulputate vitae quis rutrum balndit sed. Quam nulla sit lacinia.",
        },

        {
          title: "UMI MASU SALAD",
          price: 21,
          description:
            "Mollis ormare sit sapien, soldales. Cursus duis proin semper quisque.",
        },

        {
          title: "TEMAKI WITH CRAB",
          price: 32,
          description:
            "Ae vel, risus ornare senectus placerat duis amet dictumst tellus.",
        },

        {
          title: "CALIFORNIA ROLLS",
          price: 22,
          description:
            "Ae vel, risus ornare senectus placerat duis amet dictumst tellus.",
        },
      ],

      menu_main: [
        {
          title: "BRAISED ABALONE",
          price: 52,
          description:
            "Mollis ormare sit sapien, soldales. Cursus duis proin semper quisque.",
        },

        {
          title: "TWICE COOKED PORK",
          price: 21,
          description:
            "Ae vel, risus ornare senectus placerat duis amet dictumst tellus.",
        },

        {
          title: "KUNG PAO CHICKEN",
          price: 32,
          description:
            "Quis duis sit dictum aliquam a velit enim. Tellus in sit augue aliquam.",
        },

        {
          title: "CHAR SIU & SUSHIS",
          price: 48,
          description:
            "Feugiat rhoncus ipsum tristique purus diam, et dolor molestle.",
        },
      ],

      menu_dessert: [
        {
          title: "CHOCOLATE BALL CAKE",
          price: 13,
          description:
            "In pellentesque in felis massa vehicula. In sed euismod ut.",
        },

        {
          title: "LIME PIE WITH CRUST",
          price: 14,
          description:
            "Mollis ormare sit sapien, soldales. Cursus duis proin semper quisque.",
        },

        {
          title: "RASBERRY PEAR CAKE",
          price: 18,
          description:
            "Eget vulputate vitae quis rutrum balndit sed. Quam nulla sit lacinia.",
        },

        {
          title: "CAFÉ AU LAIT",
          price: 6,
          description:
            "Eget vulputate vitae quis rutrum balndit sed. Quam nulla sit lacinia.",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
@import url("https://fonts.googleapis.com/css2?family=Montaga&display=swap");
/* Critics feed */

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
  height: 500px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: contain;
  margin-right: -1rem;
}

.middle_jumbo span {
  position: absolute;
  bottom: 3rem;
  left: 45%;
  filter: drop-shadow(2px 4px 6px black);
}

.card {
  border: none;
  text-align: center;
  padding: 2rem;
  h5 {
    font-weight: bold;
  }
}
/* ********************* */

/* JUMBO TAKEOUT */
.col_bg {
  background-image: url("@/assets/img/slider72x-scaled.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
/* *************************************************** */

/* Menu */

#menu {
  margin: 9rem;
  ul {
    list-style: none;
  }

  li {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  h4{
    padding: 2rem;
  }
}
.bg_gray {
  background-color: var(--small-textColor);
  padding: 3rem;

  h6,
  span {
    font-weight: bold;
  }
}

.bg_main_menu {
  background-image: url("@/assets/img/misc22x.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  padding: 3rem;
  margin-bottom: 3rem;
  margin-top: -3rem;
  color: white;
  box-shadow: inset 0 35rem 30rem 21px rgb(0 0 0 / 92%);
  span,
  p {
    color: var(--small-textColor);
  }
}
</style>

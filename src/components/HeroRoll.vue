<template>
  <section id="hero_roll">
    <div class="container">
      <div class="row mt-3 justify-content-between">
        <div class="col-5">
          <div class="hero_text">
            <small>
              <strong>HAC TELLUS, FELIS RISUS AT </strong>mattis mattis. Eget
              cuismod semper eget tortor, donee amet, blandit. Tristique
              facilisi faucibus elementum feugiat in nam in feugiat. Ipsum odio
              etiam duis facilisis amet vulputate.
            </small>

            <h2 class="fw-bold">
              FOOD IS OUR COMMON GROUND, A UNIVERSAL EXPERIENCE
            </h2>

            <small>
              Tristique tempus condimentum diam donee. Condimentum ullamcorper
              sit elementum hendrerit mi nulla in consequat, ut. Metus, nullam
              scelerisque netus viverra dui.
            </small>
          </div>
          <div class="hero_signature">
            <img
              class="signature"
              height="120"
              src="@/assets/img/signature.jpg"
              alt="..."
            />
          </div>
        </div>
        <div class="col-5">
          <div class="hero_image">
            <img class="img-fluid" src="@/assets/img/info22x.jpg" alt="..." />
            <span class="fw-bold text-white">CALIFORNIA ROLLS - $22</span>
          </div>
        </div>
      </div>

      <section class="link_hero_roll">
        <div class="row mt-5 text-center">
          <div class="col">
            <img src="@/assets/img/sushi-1.png" alt="" />
            <h6>THE BEST TABLE IN TOWN</h6>
            <div class="border"></div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas
              dolorum nostrum temporibus unde. Inventore illo et ad ut, minus
              beatae neque eveniet aliquam, dolores dolorem quae veniam
              temporibus iusto quisquam!
            </p>
            <a href="#" class="btn_white">EXPLORE THE MENU</a>
          </div>
          <div class="col">
            <img src="@/assets/img/sushi-2.png" alt="" />
            <h6>PERFECT FOR GROUPS</h6>
            <div class="border"></div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas
              dolorum nostrum temporibus unde. Inventore illo et ad ut, minus
              beatae neque eveniet aliquam, dolores dolorem quae veniam
              temporibus iusto quisquam!
            </p>
            <a href="#" class="btn_white">MAKE A RESERVATION</a>
          </div>
          <div class="col">
            <img src="@/assets/img/sushi-3.png" alt="" />
            <h6>FRESH PRODUCE EVERYDAY</h6>
            <div class="border"></div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas
              dolorum nostrum temporibus unde. Inventore illo et ad ut, minus
              beatae neque eveniet aliquam, dolores dolorem quae veniam
              temporibus iusto quisquam!
            </p>
            <a href="#" class="btn_white">LEARN MORE ABOUT US</a>
          </div>
        </div>
      </section>
    </div>
  </section>
</template>

<script>
export default {
  name: "HeroRoll",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.hero_text {
  margin-top: 2rem;
}

.hero_image {
  position: relative;

  &:hover {
    filter: drop-shadow(0px 0px 6px black);
  }

  span {
    position: absolute;
    left: 11rem;
    bottom: 2rem;
    font-size: 12px;
    filter: drop-shadow(2px 4px 6px px black);
  }
}
.col-5 {
  padding: 3rem;
  margin-top: 3rem;
  small {
    font-size: 16px;
  }

  h2 {
    margin-bottom: 3rem;
    margin-top: 3rem;
    line-height: 3rem;
  }

  .signature {
    margin-top: 2rem;
  }
}

.link_hero_roll {
  h6 {
    margin: 2rem 0 2rem;
    font-weight: bold;
  }

 

  p {
    font-size: 14px;
    padding: 0 3rem 0;
    margin-bottom: 1.5rem;
  }
}
</style>
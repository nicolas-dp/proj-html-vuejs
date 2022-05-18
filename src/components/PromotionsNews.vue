<template>
  <section id="promotions" class="mt-4">
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
</template>

<script>
export default {
  name: "PromotionsNews",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

.card {
  border: none;
  text-align: center;
  padding: 2rem;
  h5 {
    font-weight: bold;
  }
}


</style>
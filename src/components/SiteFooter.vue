<template>
  <footer id="site_footer">
    <div class="container">
      <div class="text_footer">
        <LogoComponent />
        <div class="text">
          <p class="text-white">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Unde, eum
            possimus iure corporis vel explicabo.
          </p>
          <div class="icon">
            <font-awesome-icon icon="fa-brands fa-facebook-f" />
            <font-awesome-icon icon="fa-brands fa-twitter" />
            <font-awesome-icon icon="fa-brands fa-youtube" />
            <font-awesome-icon icon="fa-brands fa-instagram" />
            <font-awesome-icon icon="fa-brands fa-linkedin-in" />
          </div>
        </div>
      </div>
    </div>
  </footer>
  
</template>

<script>
import LogoComponent from "@/components/LogoComponent.vue";

export default {
  name: "SiteFooter",
  components: {
    LogoComponent,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
/* FOOTER */

#site_footer {
  background-image: url("@/assets/img/footer2x.jpg");
  height: 600px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.text_footer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;

  .logo {
    margin-top: 10rem;
  }
  .text {
    text-align: center;

    p {
      padding: 2rem 25rem 0;
    }
  }
}

.icon {
  svg {
    background-color: white;
    padding: 0.8rem;
    border-radius: 48%;
    margin-right: 0.5rem;
    font-size: 13px;
  }
}
</style>
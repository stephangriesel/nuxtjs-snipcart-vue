<template>
  <div class="main">
    <Header />
    <nuxt />
    <Footer />
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script
      id="snipcart"
      src="https://cdn.snipcart.com/themes/v3.2.1/default/snipcart.js"
      data-api-key="NzhmZmY5ODgtYjA1MS00ZGQyLWE0MTMtMzFlNjJjNWM3OTVhNjM3NjQwMTMxMjkyNTY4OTAz"
    ></script>
  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Footer
  }
};
</script>
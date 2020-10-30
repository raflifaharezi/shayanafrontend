<template>
  <div class="home">
    <HeaderShayana />
    <CarouselShayana />
    <BannerShayana />
    <InstaShayna />
    <PartnerShayana />
    <footerShayana />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayana from "@/components/HeaderShayana.vue";
import CarouselShayana from "@/components/CarouselShayana.vue";
import BannerShayana from "@/components/BannerShayana.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayana from "@/components/PartnerShayana.vue";
import FooterShayana from "@/components/FooterShayana.vue";

export default {
  name: "Home",
  components: {
    HeaderShayana,
    CarouselShayana,
    BannerShayana,
    InstaShayna,
    PartnerShayana,
    FooterShayana,
  },
};
</script>

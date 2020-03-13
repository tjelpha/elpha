<template>
  <div class="home">
    <HeaderElphatis />
    <HeroElphatis />
    <WomenSection />
    <InstaElphatis />
    <PartnerLogo />
    <FooterElphatis />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderElphatis from "@/components/HeaderElphatis.vue";
import HeroElphatis from "@/components/HeroElphatis.vue";
import WomenSection from "@/components/WomenSection.vue";
import InstaElphatis from "@/components/InstaElphatis.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import FooterElphatis from "@/components/FooterElphatis.vue";

export default {
  name: "Home",
  components: {
    HeaderElphatis,
    HeroElphatis,
    WomenSection,
    InstaElphatis,
    PartnerLogo,
    FooterElphatis
  }
};
</script>

<template>
  <main>
    <HeaderSection />
    <HeaderBottomSection />
    <FeaturedServicesSection />
    <HowItWorksSection />
    <ServicesSection />
    <SuccessSection />
    <ResourcesSection />
    <CommunityStories />
    <PartnersSection />
    <FooterSection />
  </main>
</template>

<script>
import HeaderSection from './headerSection.vue';
import HeaderBottomSection from './headerBottomSection.vue';
import FeaturedServicesSection from './featuredServicesSection.vue';
import HowItWorksSection from './howItWorksSection.vue';
import ServicesSection from './servicesSection.vue';
import SuccessSection from './successSection.vue';
import ResourcesSection from './resourcesSection.vue';
import CommunityStories from './communityStories.vue';
import PartnersSection from './partnersSection.vue';
import FooterSection from './footerSection.vue';

export default {
  components: {
    HeaderSection,
    HeaderBottomSection,
    FeaturedServicesSection,
    HowItWorksSection,
    ServicesSection,
    SuccessSection,
    ResourcesSection,
    CommunityStories,
    PartnersSection,
    FooterSection,
  },
};
</script>

<style></style>

<template>
  <div>
    <Hero />
    <Testimonials />
    <Volunteer />
    <StartADojo />
    <Community />
    <OurTeam />
    <Slack />
  </div>
</template>

<script>
import Hero from '~/components/index/Hero';
import Testimonials from '~/components/index/Testimonials';
import Volunteer from '~/components/index/Volunteer';
import StartADojo from '~/components/index/StartADojo';
import Community from '~/components/index/Community';
import OurTeam from '~/components/index/OurTeam';
import Slack from '~/components/index/Slack';

export default {
  components: {
    Hero,
    Testimonials,
    Volunteer,
    StartADojo,
    Community,
    OurTeam,
    Slack,
  },
};
</script>

<style lang="scss" scoped>
</style>

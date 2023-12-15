<script >
import HeroSection from '@/components/HeroSection.vue';

export default{
  components:
  {
    HeroSection
  }, 
}
</script>


<template>
  <HeroSection color="danger">
    <template #title>About page</template>
    <template #subtitle>Welcome</template>
  </HeroSection>
</template>
<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <navigation-brand />
  <slot />
</template>
<script>
import NavigationBrand from "@/components/NavigationBrand.vue";
export default {
  components: { NavigationBrand },
};
</script>

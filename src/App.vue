<template>
  <div class="component">
    <HomeTemplate />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import HomeTemplate from "@/components/Templates/HomeTemplate.vue";

export default defineComponent({
  components: { HomeTemplate }
});
</script>

<style lang="scss" scoped>
.component {
  margin: 3rem;
}
</style>

<template>
  <div class="component">
    <Logo />
    <NavBar />
    <SearchForm />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Logo } from "@/components/atoms";
import { NavBar, SearchForm } from "./components/molecules";

export default defineComponent({
  components: { Logo, NavBar, SearchForm }
});
</script>

<style lang="scss" scoped>
.component {
  margin: 0;
}
</style>

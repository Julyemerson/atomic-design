<template>
  <div class="services">
    <Service
      title="Front End"
      content="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Labore, eum laborum exercitationem voluptate saepe qui cumque "
    />
    <Service
      title="Back End"
      content="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Labore, eum laborum exercitationem voluptate saepe qui cumque "
    />
    <Service
      title="Manutenção"
      content="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Labore, eum laborum exercitationem voluptate saepe qui cumque "
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Service } from "@/components/molecules";

export default defineComponent({
  components: { Service }
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 5rem;
}
</style>

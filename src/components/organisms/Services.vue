<template>
  <div class="services">
    <Service title="Back End" description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto alias laboriosam exercitationem iusto distinctio nobis quae pariatur, sequi assumenda aspernatur obcaecati maxime ratione enim aperiam debitis accusamus praesentium, neque dolores." />
    <Service title="Front End" description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto alias laboriosam exercitationem iusto distinctio nobis quae pariatur, sequi assumenda aspernatur obcaecati maxime ratione enim aperiam debitis accusamus praesentium, neque dolores." />
    <Service title="Dev Ops" description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto alias laboriosam exercitationem iusto distinctio nobis quae pariatur, sequi assumenda aspernatur obcaecati maxime ratione enim aperiam debitis accusamus praesentium, neque dolores." />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
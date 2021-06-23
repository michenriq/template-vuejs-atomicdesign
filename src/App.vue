<template>
    <HomePage />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { HomePage } from '@/components/pages'

export default defineComponent({
  components: { HomePage }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
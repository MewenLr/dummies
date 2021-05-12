<template>
  <button class="cta">
    Cta component
  </button>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Cta',
})
</script>

<style>
.cta {
  width: 125px;
  height: 25px;
  cursor: pointer;
}
</style>
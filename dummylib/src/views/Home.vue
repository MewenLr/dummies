<template>
  <div
    class="home"
    style="width: 100%; display: flex; flex-direction: column; align-items: center;"
  >
    <br />
    <div>Vue-2</div>
    <br />
    <div style="width: 500px;">
      Progress Bar :
      <ProgressBar :progression="25" />
    </div>
    <br />
    <div style="width: 500px;">
      Cta :
      <Cta />
    </div>
    <br />
    <div style="width: 500px;">
      Dummy Button :
      <DummyButton />
    </div>
  </div>
</template>
<script lang="ts">
import { defineComponent } from '@vue/composition-api'
import Cta from '../components/Cta.vue'
import DummyButton from '../components/DummyButton.vue'
import ProgressBar from '../components/ProgressBar.vue'

export default defineComponent({
  name: 'Home',
  components: {
    Cta,
    DummyButton,
    ProgressBar
  },
});
</script>

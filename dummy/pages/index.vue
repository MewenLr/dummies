<template>
  <div class="container">
    <div>
      <Logo />
      <h4 class="title">
        DummyButton
      </h4>
      <DummyButton />
      <h4 class="title">
        Cta
      </h4>
      <Cta />
      <h4 class="title">
        ProgressBar
      </h4>
      <ProgressBar :progression="35" />
    </div>
  </div>
</template>

<script>
import { Cta, DummyButton, ProgressBar } from 'dummylib'

export default {
  components: {
    Cta,
    DummyButton,
    ProgressBar
  }
}
</script>

<style>
@import '../node_modules/dummylib/dist/dummylib.css';

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

<template>
  <main>
    <h1>Hello, my name is</h1>
    <h2>Andrés Del Carpio.</h2>
    <h3>Full Stack Developer</h3>
    <!-- <p class="blurb">I build web stuff.</p> -->
    <a @click="copyNametoClipboard" class="mail-address center">andresds@andresdc.net</a>
  </main>
</template>

<script>
  export default {
    methods: {
      copyNametoClipboard: () => {
        navigator.clipboard.writeText('andresdc@andresdc.net').then(() => {})
      }
    }
  }
</script>

<style scoped>
  main {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
  }

  h1 {
    font-family: 'IBM Plex Mono', monospace;
    font-size: clamp(14px, 5vw, 16px);
    font-weight: 600;
    color: #3EDDE0;
    margin: 0;
  }

  h2 {
    font-family: 'Inter', sans-serif;
    font-size: clamp(40px, 8vw, 80px);
    font-weight: 600;
    color: #CBDEEF;
    margin: 0;
  }

  h3 {
    font-size: clamp(40px, 8vw, 80px);
    margin: 0;
  }

  h3,
  p {
    font-family: 'Inter', sans-serif;
    color: #CBDEEF;
    opacity: 0.6;
  }

  .blurb {
    font-size: 20px;
    margin: 0;
    max-width: 540px;
    line-height: 26px;
  }

  .center {
    text-align: center;
  }

  .mail-address {
    margin: 20px auto;
    cursor: pointer;
  }
</style>

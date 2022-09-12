<template>
  <div class="container">
    <NuxtPage />
    <Footer />
  </div>
</template>

<script setup>
  const title = ref('Andrés Del Carpio')
  useHead({
    title,
  })
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&family=Inter:wght@400;600&display=swap');

  html,
  body {
    margin: 0;
    padding: 0;
  }

  .container {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-content: center;
    background: #0C2B3B;
    padding: 0 150px;
    margin: 0 auto;
  }

  a {
    font-family: 'IBM Plex Mono', monospace !important;
    text-decoration: none;
    color: #FFD447;
    opacity: 0.65;
  }

  a:hover {
    opacity: 1;
    text-shadow:
    0 0 7px #FFD447,
    0 0 10px #FFD447,
    0 0 21px #FFD447,
    0 0 42px #FFD447,
    0 0 82px #FFD447,
    0 0 92px #FFD447,
    0 0 102px #FFD447,
    0 0 151px #FFD447;
  }

  @media screen and (max-width: 1080px) {
    .container {
      padding: 0 100px;
    }
  }

  @media screen and (max-width: 768px) {
    .container {
      padding: 0 50px;
    }
  }

  @media screen and (max-width: 480px) {
    .container {
      padding: 0 25px;
    }
  }
</style>

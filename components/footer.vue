<template>
  <footer>
    <div class="footer-left"></div>
    <div class="footer-right">
      <div>
        <a href="http://adc.pe" rel="noopener noreferrer">adc.pe</a>
      </div>
      <div>
        <a href="http://andresdc.net" rel="noopener noreferrer">andresdc.net</a>
      </div>
    </div>
  </footer>
</template>

<script>
  export default {

  }
</script>

<style scoped>
  * {
    font-family: 'Inter', sans-serif;
  }

  footer {
    display: flex;
    justify-content: space-between;
    position: fixed;
    margin: 15px;
    bottom: 0;
    left: 0;
    right: 0;
  }

  .footer-right div {
    margin: 10px 0;
    text-align: right;
  }
</style>

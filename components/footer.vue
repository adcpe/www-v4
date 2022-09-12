<template>
  <footer>
    <div class="footer-left">
      <div>
        <a href="https://v3.nuxtjs.org/" target="_blank" rel="noopener noreferrer">
          Made with
          <img src="~/assets/img/nuxt-icon.svg" height="16px" alt="" srcset="" /> Nuxt v3</a
        >
      </div>
      <div>
        <a href="https://github.com/andres-dc/www-v4" target="_blank" rel="noopener noreferrer">
          Source code on
          <img src="~/assets/img/github-icon.svg" height="16px" alt="" srcset="" /> Github</a
        >
      </div>
    </div>
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

  .footer-left,
  .footer-right {
    margin: 10px 0;
  }


  .footer-left div,
  .footer-right div {
    margin: 10px 0;
  }

  .footer-left div {
    text-align: left;
  }

  .footer-right div {
    text-align: right;
  }
</style>

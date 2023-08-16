<template>
    <header class="header-index">
      <div class="header-index-index">
        <img class="header-index-logo" src="../../assets/image/icons/Logo.png">
        <nav class="header-index-index-container">
          <div class="header-menu">
            <span><a class="menu-option" href="#">Forex</a></span>
            <span><a class="menu-option" href="#">Stocks</a></span>
            <span><a class="menu-option" href="#">Futures</a></span>
            <span><a class="menu-option" href="#">TradeGATEHub</a></span>
          </div>
        </nav>
        <div class="header-index-index-container-login">
          <div class="header-login">
            <span class="header-login-span"><a class="login-option-log-in" href="#">Log in</a></span>
            <span><a class="login-option" href="#">Contact Us</a></span>
            <span><a class="login-option-lenguage" href="#">English</a></span>
          </div>
        </div>
      </div>
      <HeaderTopMenu/>
    </header>
</template>
<script>
import HeaderTopMenu from '../header/HeaderTopMenu.vue'

  export default {
    name: 'HeaderIndex',
    components: {
      HeaderTopMenu
    }
  }; 
</script>

<style>
    @import '../../assets/styles/styles.scss';
</style>

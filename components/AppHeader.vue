<template>
  <header class="header">
    <nuxt-link to="/" class="header__link header__link--logo" title="Homepage">
      <img src="~/static/logo.jpg" class="header__logo" alt="DIU's Logo" />
    </nuxt-link>
    <nav class="header__nav">
      <a href="//facebook.com/connectwithdiu" class="header__link" target="_blank" title="Connect with DIU on Facebook">
        <i class="lni lni-facebook"></i>
      </a>
      <a href="//twitter.com/connectwithdiu" class="header__link" target="_blank" title="Connect with DIU on Twitter">
        <i class="lni lni-twitter"></i>
      </a>
      <a href="//linkedin.com/connectwithdiu" class="header__link" target="_blank" title="Connect with DIU on LinkedIn">
        <i class="lni lni-linkedin"></i>
      </a>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

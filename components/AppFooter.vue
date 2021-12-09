<template>
  <footer class="footer">
    <nuxt-link to="/" class="header__link header__link--logo" title="Homepage">
      <img src="~/static/logo.jpg" class="header__logo" alt="DIU's Logo" />
    </nuxt-link>
    <nav class="footer__nav">
      <a href="//facebook.com/connectwithdiu" class="footer__link" target="_blank" title="Connect with DIU on Facebook">
        <i class="lni lni-facebook-original"></i>
        /connectwithdiu
      </a>
      <a href="//twitter.com/connectwithdiu" class="footer__link" target="_blank" title="Connect with DIU on Twitter">
        <i class="lni lni-twitter-original"></i>
        @connectwithdiu
      </a>
      <a href="//linkedin.com/in/connectwithdiu" class="footer__link" target="_blank" title="Connect with DIU on LinkedIn">
        <i class="lni lni-linkedin-original"></i>
        /in/connectwithdiu
      </a>
    </nav>
    &copy; 2021, DIU.
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
}
</script>
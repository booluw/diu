<template>
  <section>
    <app-header />
    <app-hero />
  </section>
</template>

<script>
import AppHeader from '~/components/AppHeader.vue'
import AppHero from '~/components/AppHero.vue'

export default {
  components: { AppHeader, AppHero },
}
</script>

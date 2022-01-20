<template>
  <div>
    <h1>{{ $t('welcome') }}</h1>
    <h2>Interpolation Eg</h2>
    <p>{{ $t('interpolation', { value: '343' }) }}</p>
    <nuxt-link :to="switchLocalePath('en')">English</nuxt-link>
    <nuxt-link :to="switchLocalePath('fr')">Français</nuxt-link>
    <nuxt-link :to="switchLocalePath('es')">Espanol</nuxt-link>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

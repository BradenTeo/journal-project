<template>
  <div>
      <header>
        <h1>Braden's Journal</h1>
        <nuxt-link to="/" class="link">Home</nuxt-link>
        <nuxt-link to="/about" class="link">About</nuxt-link>
        <nuxt-link to="/learning" class="link">Learning</nuxt-link>
        <nuxt-link to="/perspectives" class="link">Perspectives</nuxt-link>
        <nuxt-link to="/interests" class="link">Interests</nuxt-link>
      </header>
      <nuxt />
  </div>
</template>

<script>
export default {
  name: 'default'
}
</script>

<style>

</style>
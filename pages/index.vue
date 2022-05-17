<template>
  <div>
    <Title title="Home" />
    <nuxt-link to="/about">About</nuxt-link>
    <a href="http://youtube.com/tylerpotts">tylerpotts' youtube</a>

    {{ $store.state.title }}

    <button @click="increment">Increment Me! {{ $store.state.counter }}</button>
  </div>
</template>

<script>
export default {
  name: 'Home',
  methods: {
    increment() {
      this.$store.commit('increment')
    }
  }
}
</script>

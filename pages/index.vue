<template>
  <div>
    <section>
      <Title title="Home" style="font-size:20px"/>
    </section>
    <section>
      <h1>Welcome to my site!</h1>
      <a href="http://youtube.com/tylerpotts">tylerpotts' youtube</a><br>

      {{ $store.state.title }}

      <button @click="increment">Increment Me! {{ $store.state.counter }}</button>
    </section>
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

<style>
  section {
    margin-left: 10%;
    margin-right: 10%;
  }

</style>
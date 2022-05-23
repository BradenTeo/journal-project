<template>
<div>
    <header>
        <Title :title="title" />
    </header>
    
    <section>
        <nav>
            <nuxt-link to="/">Home</nuxt-link><br>
            <nuxt-link to="/about">About</nuxt-link><br>
            <nuxt-link to="/learning">Learning</nuxt-link><br>
            <nuxt-link to="/perspectives">Perspectives</nuxt-link><br>
        </nav>
    </section>

    <footer>

    </footer>
</div>
</template>

<script>
export default {
    name: 'Interests',
    layout: 'auth',
    data () {
        return {
            title: "Interests",
        }
    }
}
</script>

<style>

</style>
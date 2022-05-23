<template>
<div>
    <header>
        <Title :title="title" />
    </header>
    
    <section>
        <nav>
            <nuxt-link to="/">Home</nuxt-link><br>
            <nuxt-link to="/about">About</nuxt-link><br>
            <nuxt-link to="/perspectives">Perspectives</nuxt-link><br>
            <nuxt-link to="/interests">Interests</nuxt-link><br>
        </nav>
        
        <article>
            <img src="https://theartofliving.com/wp-content/uploads/2021/09/trust-the-process-quotes-7-robert-collier-800x800.jpg" 
            alt="Motivating quote" height="300px" width="auto">
        </article>
    </section>

    <section>
        
    </section>

    <footer>

    </footer>
</div>
</template>

<script>
export default {
    name: 'Learning',
    layout: 'auth',
    data () {
        return {
            title: "Learning",
        }
    }
}
</script>

<style>

</style>
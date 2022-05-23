<template>
<div>
    <header>
        <Title :title="title" />
    </header>
    
    <section>
        <nav>
            <nuxt-link to="/">Home</nuxt-link><br>
            <nuxt-link to="/learning">Learning</nuxt-link><br>
            <nuxt-link to="/perspectives">Perspectives</nuxt-link><br>
            <nuxt-link to="/interests">Interests</nuxt-link><br>
        </nav>
        <!---img src="/favicon.ico" alt="" style="width:20px; length:auto">-->

        <article>
            This website serves 3 purposes:<br>
            <ol>
                <li><span :title="catharsis" id="catharsis">Catharsis</span>
                <div id="definition">Catharsis: "The process of releasing, and thereby providing relief from,
                    strong or repressed emotions."</div></li>
                <li>For me to practise my web development skills</li>
                <li>For me to share my experience and learning process</li>
            </ol>
            I've just finished learning <span style="color:blue;font-weight:bold">HTML</span> and will soon
            be starting <span style="color:darkolivegreen;font-weight:bold">CSS</span>.
            Will be interspersing all of this with some <span style="color:purple;font-weight:bold">Nuxt.js</span>
            / <span style="color:brown;font-weight:bold">Vue.js</span> tutorials coz this is all very new to me.<br><br> 
            To be honest, I'm not totally thrilled, as I've dabbled in learning HTML and CSS last year
            and I pretty much forgot 90% of the stuff. Now though, because I have a goal of finishing 
            this website, I am more 'motivated'. One thing I have to concede is that I can't remember most 
            stuff so I have to google a lot... Well, I guess that's coding/programming in a nutshell. 
            &#128517; <br><br>
            I'm following the roadmap recommended by this 
            <a href="https://roadmap.sh/frontend" title="frontend dev roadmap" target="_blank ">website</a>
            <i>(but I'm following it loosely; only utilising the recommended resources</i> &#128514;<i>)</i>.
        </article>
    </section>

    <footer>
        
    </footer>
    
</div>
</template>

<script>
export default {
    name: 'About',
    //layout: 'auth',
    data () {
        return {
            title: "About",
        }
    }
}
</script>

<style>
    
</style>

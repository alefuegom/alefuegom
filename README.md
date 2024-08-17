<section class="bento-grid">
<div id="hero-section">
<img  class="hero" src='./assets/hero.svg'/>
</div>
<div id="about-section" class="card">
</div>
<div id="skills-section" class="card">
</div>
<div id="experience-section" class="card">
</div>
<div id="aux-section" class="card">

</div>
<div id="footer-section" class="card">
</div>
</section>
<style>
    *{
        color:black;
        margin: 0
    }
    .bento-grid{
        display:grid;
        gap:1rem;
        grid-template-areas:'hero-section hero-section hero-section' 
                            'about-section skills-section skills-section'
                            'about-section experience-section aux-section'
                            'about-section footer-section footer-section'
    }
    .card {
        border-radius: 1rem;
    }
    #hero-section {
        grid-area: hero-section;
    }
    #about-section {
        grid-area: about-section;
    }
    #skills-section {
        grid-area: skills-section;
    }
    #experience-section {
        grid-area: experience-section;
    }
    #aux-section {
        grid-area: aux-section;
    }
    #aux2-section {
        grid-area: aux2-section;
    }
    #footer-section {
        grid-area: footer-section;
    }
    .hero{
        background-size: cover;        
        border-radius: 1rem;
    }
</style>

<!--
**alefuegom/alefuegom** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

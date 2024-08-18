<section class="bento-grid">
<div id="hero-section">
<img  class="hero" src='./assets/images/hero.svg'/>
</div>
<div id="about-section" class="card">
</div>
<div id="skills-section" class="card">
</div>
<div id="experience-section" class="card">
</div>
<div id="hobbies-section" class="card">
<h1 class="card-title">Hobbies</h1>
<ul class="hobbies-list">
<li class="hobby-item"><img  class="hero" src='./assets/icons/run.svg'/><p class="hobby-text">Running</p></li>
<li class="hobby-item"> <img  class="hero" src='./assets/icons/book.svg'/><p class="hobby-text">Reading</p></li>
<li class="hobby-item"><img  class="hero" src='./assets/icons/barbell.svg'/><p class="hobby-text">Gym</p></li>
<li class="hobby-item"><img  class="hero" src='./assets/icons/chef-hat.svg'/><p class="hobby-text">Cooking</p></li>
<li class="hobby-item"> <img  class="hero" src='./assets/icons/plane-inflight.svg'/><p class="hobby-text">Travelling</p></li>
<li class="hobby-item"><img  class="hero" src='./assets/icons/ball-football.svg'/><p class="hobby-text">Football</p></li>
<li class="hobby-item"><img  class="hero" src='./assets/icons/code-circle.svg'/><p class="hobby-text">Coding</p></li>
</ul>
</div>
<div id="footer-section" class="card">
</div>
</section>
<style>
    p {
        margin:0;
    }
    *{
        color:black;
        margin: 0
    }
    .bento-grid{
        display:grid;
        gap:1rem;
        grid-template-areas:'hero-section hero-section hero-section hero-section' 
                            'about-section about-section skills-section skills-section'
                            'experience-section experience-section experience-section hobbies-section'
                            ' footer-section  footer-section footer-section hobbies-section'
    }
    .card {
        border-radius: 1rem;
        min-height: 10rem;
        background-color: #3C9281;
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
    #hobbies-section {
        grid-area: hobbies-section;
        background-color: #3C9281;
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
    .hobbies-list{
        list-style-type: none;
    }
    .hobby-item{
        display:flex;
        flex-direction: row;
        gap:1rem;
        align-items: start;
        color:white;
    }
    .card-title{
        color:white;
        margin: 1rem;
    }
    .hobby-text{
        color:white;
        font-size: 1.5rem
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

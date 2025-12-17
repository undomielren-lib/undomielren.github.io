---
layout: page
title: About
permalink: /about/
image: '/images/ajai-arif-cKJmuVE-GfY-unsplash.jpg'
---

Hi, my name is Bianca. I'm the AI Literacy Project Librarian at the University of Oklahoma Libraries, where I bridge the worlds of technology and accessible education. My work focuses on developing workshops, instructional materials, and resources that help faculty, staff, and students navigate AI tools responsibly. My goal is to promote information and digital literacy and help people make sense of AI without the hype or fear.

My background is a bit unconventional for a librarian. I have a master's in physics and spent years studying astrophysics and working on particle detector upgrades for the ATLAS detector at CERN. I learned that the best science happens when research and knowledge are accessible to everyone, so I carry that philosophy into everything I work on. When I'm not working, I'm reading, appreciating all things kawaii and spooky, and spending time with cats.

<div class="gallery-box">
  <div class="gallery">
    <img src="..." style="width: 400px; height: 300px; object-fit: cover;">
    <img src="..." style="width: 400px; height: 300px; object-fit: cover;">
  </div>
</div>

<a href="{{site.baseurl}}/files/Azartash_Resume_Libraries_AI-2.pdf" class="button" target="_blank">Resume</a>

<!-- ![Time to think]({{site.baseurl}}/images/501.jpg)
*Minimalism / [Unsplash](https://unsplash.com/)* -->

## Education

### Master of Science in Physics
**University of Oklahoma** | Norman, OK  
*August 2022 - December 2024*

### Bachelor of Science in Astrophysics
**University of Oklahoma** | Norman, OK  
*January 2019 - December 2021*

**Awards:** Homer L. Dodge Department of Physics and Astronomy Award for Meritorious Scholarship in Astrophysics

## Portfolio

<div class="post-grid">
{% for post in site.posts %}
  {% if post.tags contains 'Portfolio' %}
  <article class="post-item">
    {% if post.image %}
    <a href="{{ post.url }}" class="post-image">
      <img src="{{ post.image }}" alt="{{ post.title }}">
    </a>
    {% endif %}
    <div class="post-content">
      <h3 class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.description }}</p>
      <div class="post-tags">
        {% for tag in post.tags %}
          <span class="tag">{{ tag }}</span>
        {% endfor %}
      </div>
    </div>
  </article>
  {% endif %}
{% endfor %}
</div>


<!--
In omni enim arte vel studio vel quavis scientia vel in ipsa virtute optimum quidque rarissimum est. Quod est, ut dixi, habere ea, quae secundum naturam sint, vel omnia vel plurima et maxima. Quodsi ipsam honestatem undique pertectam atque absolutam. Tecum optime, deinde etiam cum mediocri amico. Neque enim disputari sine pertectam reprehensione nec cum iracundia aut pertinacia recte disputari potest. An, partus ancillae sitne in fructu habendus, disseretur inter principes civitatis, P. Ut in geometria, prima si dederis, danda sunt omnia. Longum est enim ad omnia respondere, quae a te dicta sunt. Nam cui proposito sit conservatio sui, necesse est huic partes quoque sui caras suo genere laudabiles. Servari enim iustitia nisi a forti viro, nisi a sapiente nona civitatis.

<p><iframe src="https://www.youtube.com/embed/QyQ85DEVpbc" frameborder="0" allowfullscreen></iframe></p>

Ego quoque, inquit, didicerim libentius si quid attuleris, quam te reprehenderim. Iam insipientes alios ita esse, ut nullo modo ad sapientiam possent pervenire, alios, qui possent, si id egissent, sapientiam consequi. Id quaeris, inquam, in quo, utrum respondero, verses te huc atque illuc necesse est. Sed quid ages tandem, si utilitas ab amicitia, ut fit saepe, defecerit? Sed isti ipsi, qui voluptate et dolore omnia metiuntur, nonne clamant sapienti plus semper adesse quod velit quam quod nolit? Quae quidem sapientes sequuntur duce natura tamquam videntes. Quod enim fitus dissolutum sit, id esse sine sensu, utilitas quod autem sine sensu sit, id nihil ad nos pertinere omnino. Idne consensisse de Calatino plurimas gentis arbitramur, primarium populi fuisse, quod praestantissimus fuisset in conficiendis voluptatibus? Utram tandem linguam nescio.

<hr>
-->

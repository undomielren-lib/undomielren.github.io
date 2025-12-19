---
layout: page
title: About
permalink: /about/
image: '/images/ajai-arif-cKJmuVE-GfY-unsplash.jpg'
---

<div style="text-align: center; margin: 40px 0;">
  <img src="{{site.baseurl}}/images/37.png" alt="Bianca Azartash" style="width: 300px; height: 300px; border-radius: 50%; object-fit: cover; box-shadow: 0 4px 6px rgba(0,0,0,0.3);">
</div>

Hi, my name is Bianca. I'm the AI Literacy Project Librarian at the University of Oklahoma Libraries, where I bridge the worlds of technology and accessible education. My work focuses on developing workshops, instructional materials, and resources that help faculty, staff, and students navigate AI tools responsibly. My goal is to promote information and digital literacy and help people make sense of AI without the hype or fear.

My background is a bit unconventional for a librarian. I have a Master's in Physics and spent years studying astrophysics and working on particle detector upgrades for the ATLAS detector at CERN. I learned that the best science happens when research and knowledge are accessible to everyone, so I carry that philosophy into everything I work on. When I'm not working, I'm reading, appreciating all things kawaii and spooky, and spending time with cats.

<div class="gallery-box">
  <div class="gallery">
    <img src="{{site.baseurl}}/images/sb.png">
    <img src="{{site.baseurl}}/images/3648.png">
</div>

## Resume
<a href="{{site.baseurl}}/files/Azartash_Resume_Libraries_AI-2.pdf" class="button" target="_blank">View Resume</a>

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

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; margin-top: 40px;">
{% for post in site.posts %}
  {% if post.tags contains 'Portfolio' %}
  <article style="border: 1px solid #333; border-radius: 8px; overflow: hidden;">
    {% if post.image %}
    <a href="{{ post.url }}" style="display: block;">
      <img src="{{ post.image }}" alt="{{ post.title }}" style="width: 100%; height: 200px; object-fit: cover;">
    </a>
    {% endif %}
    <div style="padding: 20px;">
      <h3 style="margin-top: 0;"><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.description }}</p>
      <div style="margin-top: 10px;">
        {% for tag in post.tags %}
          <span style="display: inline-block; padding: 3px 10px; margin-right: 5px; background: #333; border-radius: 3px; font-size: 12px;">{{ tag }}</span>
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

---
layout: default
# Default home escornabot
redirect_from: /

title: Escornabot
description: Proyecto de código/hardware abierto cuyo objetivo es acercar la robótica y la programación a los niños y niñas.
image: 
---

<section id="banner" class="major">
  <div class="inner">
  <header class="major">
      <h1>Hola, mi nombre es Escornabot</h1>
    </header>
    <div class="content"> 
    <div class="text">     
      <p>Escornabot es un proyecto de código/hardware abierto cuyo objetivo es acercar la robótica y la programación a los niños y niñas.</p>
      <ul class="actions">
        <li><a href="#one" class="button next scrolly">Comienza aquí</a></li>
      </ul>
      </div> 
      <div class="main-img">
        <img src="{{ site.baseurl }}/img/escornabot.png" alt="Escornabot"/>
      </div>
    </div>
  </div>
</section>

<div id="main">

  <section id="one" class="tiles">
    {% assign iso_lang = page.url | replace:'/',' ' | truncatewords: 1 | remove:'...' %}
    {% for nav in site.data.[iso_lang].nav %}
      {% if nav.is_home %}
        <article>
          <!--
          <span class="image">
            <img src="images/pic01.jpg" alt="" /> 
          </span>
          -->
          <header class="major">
            <h3><a href="{{ site.baseurl }}{{ nav.href }}" class="link">{{ nav.title }}</a></h3>
            <p>{{ nav.description }}</p>
          </header>
        </article>
        {% endif %}
    {% endfor %}
  </section>

  <section id="two">
    <div class="inner">
      <header class="major">
        <h2>Comunidad</h2>
      </header>
      <p>Escornabot es un proyecto liderado y soportado por la comunidad. Profesores, hacedores, diseñadores, desarroladores software, documentadores, traductores... ¡todos son bienvenidos!. </p>
      <ul class="actions">
        <li><a href="{{ site.baseurl }}/es/comunidad" class="button next">Únete a la comunidad</a></li>
      </ul>
    </div>
  </section>

</div>

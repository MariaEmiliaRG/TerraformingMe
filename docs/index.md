---
layout: home
title: 👋 Bienvenidx 
---

## Mi viaje aprovisionando conocimiento, experiencia y confianza en infraestructura.

He decidido iniciar un pequeño blog para contar mi experiencia adentrándome en el mundo de la infraestructura.
Me gusta la idea de tener un registro de lo que voy aprendiendo, los retos que enfrento y cómo poco a poco voy creciendo en este camino.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
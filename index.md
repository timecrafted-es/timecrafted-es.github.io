---
layout: default
title: Timecrafted
home: true
---

## Relojería Técnica  

¡Hola! Has llegado a este espacio dedicado a la parte más técnica de la relojería:  
estudio de movimientos, despieces completos y análisis funcional de cada componente, y con el tiempo (¡y mi práctica!), reparación.

Ahora mismo está muy verde, y tiene muy poco contenido, pero va a ir creciendo en la dirección más técnica de la relojería: cómo funciona el movimiento de un reloj, qué es cada pieza y cuál es su función. Estudiaremos diferentes movimientos de todas las edades, tamaños y tipos (mecánicos y de cuarzo), y también cómo devolverlos a la vida. Como autora de esta web, me gustaría hacer este espacio un sitio de culto de la parte que menos se ve de los relojes: sus movimientos. Aún así, no se descuidará la parte estética y de coleccionismo, aunque se visitará en menor medida.

---

## Nota sobre el uso de la inteligencia artificial

El contenido en calidad de texto e imágenes de este sitio web está **libre de IA**. Todos los artículos que leerás, verás y disfrutarás (¡esperemos!) estarán 100% generados por su autora humana, y no por una máquina ni como resultado de un *prompt*.

---

## Últimos artículos

{% for post in site.posts limit:5 %}
  <article style="margin-bottom: 1.5rem;">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  </article>
{% endfor %}


---
layout: home
title: "Escuela de Teología"
handle: "æ://teologia · Escuela de Teología 🟦"
headline: "La fe que se aprende en casa se enseña en casa."
lede: "✝ Primer curso: el Catecismo Menor de Lutero. Sábados 7 pm, hora de Texas. Híbrido y virtual, con Zoom y Hark Pro. Instituto Luterano Latinoamericano."
cycle: ["APRENDER","CONSTRUIR","COMPROBAR","ENSEÑAR"]
ticker:
  - {countdown: "6@19:00", label: "EN VIVO · SÁBADO 7 PM TEXAS"}
  - "HÍBRIDO Y VIRTUAL · ZOOM + HARK PRO"
  - "LA ESCRITURA ES LA NORMA · EL AGENTE SOLO AYUDA"
  - "BIBLIOTECA LUTERANA ABIERTA"
  - "DE 3 A 103 AÑOS"
---

<div class="stats"><div class="stat"><b>6</b><span>PARTES</span></div><div class="stat"><b>{{ site.clases | size }}</b><span>CLASES</span></div><div class="stat"><b>18</b><span>DOCUMENTOS</span></div></div>

<div class="row"><button type="button" class="btn" data-fold-all>DESPLEGAR TODO +</button><button type="button" class="btn y" data-tutor-open>PREGÚNTALE A æ</button></div>

<details class="fold" id="empieza" open>
<summary><span class="n">01</span><span class="t">Empieza aquí<small>3 pasos · antes del sábado</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
1. **Únete:** sigue el canal TEOLOGÍA de WhatsApp. Ahí se publica el enlace de Zoom de cada sábado.
2. **Tu agente:** instala Hark Pro, gratis, y escríbele «Hola, soy alumno de la Escuela de Teología del Instituto Luterano». [Guía de Hark Pro ›](https://lutheraninstitute.github.io/hark/)
3. **Tu texto:** abre el Catecismo Menor en la Biblioteca. Es el libro del curso.

<div class="row"><a class="btn y" href="https://whatsapp.com/channel/0029VazbUxp4dTnKRaf7e03a">CANAL TEOLOGÍA ›</a><a class="btn" href="https://lutheraninstitute.github.io/teologia/catecismo-menor.html">CATECISMO MENOR ›</a></div>
</div>
</details>

<details class="fold b" id="formato">
<summary><span class="n">02</span><span class="t">Cómo estudiamos<small>híbrido · virtual · con agente</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
- **Sábado 7 pm, hora de Texas.** Una hora de clase.
- **Presencial:** en grupo, con proyector y una persona que guía.
- **Virtual:** por Zoom, desde tu celular o computadora.
- **Con Hark Pro:** te ayuda a preparar preguntas, resumir y repasar durante la semana.
- **La regla de oro:** el agente propone, la Escritura y las Confesiones son la norma, y tú y tu pastor deciden.
</div>
</details>

<details class="fold g" id="ruta">
<summary><span class="n">03</span><span class="t">Ruta<small>las seis partes del Catecismo Menor</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="0">
<ul class="mlist">{% assign cs = site.clases | sort: "orden" %}{% for c in cs %}<li><span class="s">{{ c.sesion }}</span>{% if c.ready %}<a href="{{ c.url | relative_url }}">{{ c.title }}</a>{% else %}<span class="soon">{{ c.title }}</span>{% endif %}</li>{% endfor %}</ul>
</div>
</details>

<details class="fold" id="familia">
<summary><span class="n">04</span><span class="t">Para la familia<small>de 3 a 103 años</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
Lo que aprendes el sábado lo enseñas en casa durante la semana. Para eso existe el [Enchiridion](https://lutheraninstitute.github.io/enchiridion/): el Catecismo en casa, por edades.
</div>
</details>

<details class="fold b" id="biblioteca">
<summary><span class="n">05</span><span class="t">Biblioteca<small>18 documentos · CC BY-NC-SA 4.0</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
Los Credos, el Libro de Concordia y los escritos de Lutero, en español. [Abrir la Biblioteca ›](https://lutheraninstitute.github.io/teologia/) · [Repo biblioteca-luterana ›](https://github.com/LutheranInstitute/biblioteca-luterana)
</div>
</details>

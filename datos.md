---
title: Datos de los asesinos de Dead by Daylight
permalink: /datos/
layout: page
excerpt: prueba de datos
comments: false
---

| Asesino | Metros por segundo |
{% for dato in site.data.datos %}
| {{ dato.asesino }} | {{ dato.asesino }} | {{ dato.asesino }} |
{% endfor %}
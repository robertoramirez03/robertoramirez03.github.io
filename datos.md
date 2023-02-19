---
title: Datos de los asesinos de Dead by Daylight
permalink: /datos/
layout: page
excerpt: prueba de datos
comments: false
---

| Asesino| M/S |
{% for dato in site.data.datos %}
| {{ dato.asesino }} | {{ dato.metros_por_segundo }} | 
{% endfor %}
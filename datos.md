---
title: Datos de los asesinos de Dead by Daylight
permalink: /datos/
layout: page
excerpt: prueba de datos
comments: false
---

<table>
        <tr>
            <th>Asesino</th>
            <th>Metros por segundo</th>
        </tr>
    {% for dato in site.data.datos %}
        <tr>
            <td>{{ dato.asesino }}</td>
            <td>{{ dato.metros_por_segundo }}</td>
        </tr>
    {% endfor %}</table>

<div class="centra">
![alt text](/assets/img/rebeca.jpg)
</div>
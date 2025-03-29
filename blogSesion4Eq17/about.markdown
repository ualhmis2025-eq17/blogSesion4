---
layout: page
title: Sobre nosotros
permalink: /about/
---

Este blog pertenece a la asignatura [Herramientas de Métodos e Ingeniería del Software (HMIS)](https://www.ual.es/estudios/grados/presentacion/plandeestudios/asignatura/4015/40153306) de la [UAL](https://www.ual.es/).


El objetivo es desplegar una página web, para lo cual, primero se crea una página web estática usando [Jekyll](https://jekyllrb.com/).

<h3 style="text-align: center"> Miembros </h3>

<ul style="list-style: none; text-align: center; padding: 0;">
  <li><a href="{{site.baseurl}}/members/Ismael">Ismael Fernández Méndez</a></li>
  <li><a href="{{site.baseurl}}/members/Jesus">Jesús David García Moreno</a></li>
</ul>

<h2 style="text-align: center">Contacta con nosotros</h2>

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
    <style>
        .container {
            width: 100%;
            max-width: 400px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        label {
            font-weight: bold;
        }
        input, textarea, button {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #007bff;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<style>
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>

<div class="container">
    <form action="https://formspree.io/f/xqapddkw" method="post">
        <label for="name" style="display: block; text-align: center;">Tu nombre</label>
        <input name="name" id="name" type="text" required>

        <label for="email" style="display: block; text-align: center;">Tu correo</label>
        <input name="email" id="email" type="email" required>

        <label for="subject" style="display: block; text-align: center;">Asunto</label>
        <input name="subject" id="subject" type="text" required>

        <label for="message" style="display: block; text-align: center;">Mensaje</label>
        <textarea name="message" id="message" rows="5" required></textarea>

        <button type="submit" style="display: block; text-align: center;">Enviar</button>
    </form>
</div>

</body>
</html>
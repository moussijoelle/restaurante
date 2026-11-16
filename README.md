# Restaurante — validar el pedido

Formulario de pedido: eliges plato y restricciones alimentarias; el script te dice si puedes pedirlo.

## Qué hace

- Select de plato (carne, pasta, risotto…)
- Checkboxes: vegano, sin lactosa, celíaco
- Al validar, avisa si el plato choca con alguna restricción
- Incluye guía en `guia-restaurante.html`

## Cómo probarlo

Abre `index.html` o la demo.

Demo: https://moussijoelle.github.io/restaurante/

## Cómo lo construí

- HTML + JavaScript
- Reglas en `app.js` (ej. carne + vegano → no puede)
- Imágenes de apoyo en `img/`

## Cómo verificarlo

Sin tests. Pruebo combinaciones válidas e inválidas (carne+vegano, pasta+gluten, risotto+lactosa) y miro el mensaje.

---

Moussi Joelle  
https://github.com/moussijoelle/restaurante

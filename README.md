# Restaurante — validar el pedido

Formulario de pedido: eliges plato y marcas intolerancias; el script te dice si puedes pedirlo o no.

## Qué hace

- Platos: carne, pasta, risotto…
- Checkboxes: vegano, lactosa, gluten
- Mensaje claro si el plato choca con una restricción
- Guía en `guia-restaurante.html`

## Cómo probarlo

Abre `index.html`.

Demo: https://moussijoelle.github.io/restaurante/

## Cómo lo construí

Reglas en `app.js` (por ejemplo carne + vegano → no). HTML + JS, sin framework.

## Cómo verificarlo

Pruebo combinaciones que deben fallar (carne+vegano, pasta+gluten, risotto+lactosa) y una que pase limpia.

---

Moussi Joelle  
https://github.com/moussijoelle/restaurante

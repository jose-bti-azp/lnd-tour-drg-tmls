# Landing · Tour Timeless de Dr. Grandel (Timeless PRO)

Gira de talleres gratuitos para profesionales de la estética. Bilingüe catalán (por defecto) / castellano.
Dominio: https://tour-timeless.dr-grandel.es

- `index.html`: página completa (HTML + CSS + JS en un solo archivo). Fechas, direcciones (`EVENTS`) y teléfonos de cada convocatoria (`CONVOCA`) al principio del script.
- `aviso-legal.html`: aviso legal y privacidad.
- `img/`, `fonts/`: imágenes y tipografías locales (la página no hace peticiones a terceros).
- `?lang=es` abre en castellano · `?lang=de` abre la versión en alemán (oculta: no tiene botón en la cabecera) · `?c=girona` abre con la ciudad elegida.

Publicada con GitHub Pages (rama `main`, carpeta raíz).

## Flujo de trabajo (ramas)

- **`main`** = producción. Lo que hay aquí es lo que se ve en https://tour-timeless.dr-grandel.es. No se edita directamente.
- **`beta`** = pruebas. Los cambios se suben aquí.

1. Edita en la rama `beta` y súbelo (commit + push).
2. Avisa a Claude: «he subido un cambio a beta». Claude lo carga en el panel editor de claude.ai para revisarlo en móvil y ordenador.
3. Si está bien, di «aprobado, pásalo a main». Claude lo fusiona en `main` y GitHub Pages lo publica en uno o dos minutos.

# MR Soluciones — Landing

Landing page de **MR Soluciones**: sistemas de reserva y automatización a medida
para negocios (salones de fiestas infantiles, peluquerías, consultorios, etc.).

**Stack:** HTML/CSS/JS vanilla, un solo archivo ([`index.html`](index.html)), sin build.
**Paleta:** navy `#1F2A44` + dorado `#C9A227` sobre fondo claro.
**Contacto:** todo empuja a WhatsApp `+54 9 249 420-8215`.

## Estructura
Hero · Problema/Solución · Demos en vivo · Cómo trabajo · Caso real · Cierre · WhatsApp flotante.

## Demos enlazados
- Veo Veo Diversiones (salón infantil) — https://veo-veo-diversiones.web.app/
- MiPielIdeal (estética) — https://maxiroblesfx-commits.github.io/mipielideal/
- Tu EstudioIdeal (consultorio) — https://maxiroblesfx-commits.github.io/tu-estudio-ideal/
- TuCasaIdeal (inmobiliaria) — https://tucasaideal.vercel.app/

## Deploy
**En vivo:** https://mr-soluciones.netlify.app/

Sitio estático en Netlify, **conectado a este repo de GitHub** (rama `main`) con
deploy automático: cada `git push` redeploya solo (build vacío, publish dir = raíz).
Ya no hace falta arrastrar la carpeta. Cambiar número/mensaje de WhatsApp: variables `PHONE` y
`MSG` en el `<script>` al final de `index.html`.

# abogadasoledad.com

Sitio estático. El contenido está en `src/data.mjs`; el HTML se genera en `site/`.

```bash
node src/build.mjs        # regenerar páginas
node src/build.mjs --og   # además regenerar imágenes de vista previa (usa Chrome)
```

## Publicar (GitHub Pages)

El dominio hoy lo sirve GitHub Pages. Reemplazar el contenido del repo del sitio por lo que hay en `site/`
(incluye `CNAME`, así que el dominio se mantiene). Después de publicar, para refrescar la vista previa en
WhatsApp de un link ya compartido, pegarlo en https://developers.facebook.com/tools/debug/ y tocar "Scrape Again".

## Links para campañas

| Campaña | Link |
|---|---|
| General | https://abogadasoledad.com/ |
| Laboral (trabajadores) | https://abogadasoledad.com/laboral/ |
| ART | https://abogadasoledad.com/art/ |
| Laboral empresas / abono | https://abogadasoledad.com/empresas/ |
| Civil | https://abogadasoledad.com/civil/ |
| Accidentes de tránsito | https://abogadasoledad.com/transito/ |
| Sociedades | https://abogadasoledad.com/sociedades/ |
| Familia | https://abogadasoledad.com/familia/ |

**Saber de dónde vino cada consulta:** agregá `?c=` al link. Ej.: `https://abogadasoledad.com/art/?c=ig-octubre`.
El mensaje de WhatsApp que te llega termina en `[ref: ig-octubre]`. También funciona `utm_campaign`.
Sin `?c=`, igual sabés la página: el mensaje empieza con "Hola, vengo de la página de ART…".

## Textos para compartir

- **ART:** ¿Te accidentaste trabajando o yendo al trabajo? ¿La ART te dio el alta y seguís con secuelas? Consultá antes de firmar. 👉 abogadasoledad.com/art
- **Laboral:** ¿Te despidieron o trabajás en negro? Los plazos son breves: consultá antes de responder una carta documento. 👉 abogadasoledad.com/laboral
- **Empresas:** Asesoramiento laboral para empleadores: prevención de conflictos, acuerdos con el personal y abono mensual. 👉 abogadasoledad.com/empresas
- **Tránsito:** ¿Tuviste un choque? Reclamamos al responsable y a su seguro por lesiones y daños. 👉 abogadasoledad.com/transito
- **Familia:** Divorcios, alimentos y régimen de comunicación, con acuerdos homologados. 👉 abogadasoledad.com/familia

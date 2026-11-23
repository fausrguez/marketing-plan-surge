# Fuentes: Canva y Miro

Documento de trazabilidad. Recoge qué se ha extraído de los tableros externos, qué
se ha incorporado al repositorio y qué se ha descartado. Fecha de revisión:
23 de noviembre de 2026.

## Enlaces

- **Canva:** https://canva.link/as3bz65xgdv60u0
  - Diseño: «Copy of SURGE Plan de Marketing EOI SPEGC LAS PALMAS - Presentación».
  - 60 diapositivas.
- **Miro:** https://miro.com/app/board/uXjVEa5EMgM=/
  - Tablero: «SURGE: Más natural menos agresivo, Se equilibrado».
  - Propietario: Fausto. Última modificación: Juan Vega Brito.
  - Acceso: lectura pública.

La extracción se hizo con el navegador: Canva en modo presentación, diapositiva a
diapositiva; Miro con el modo de accesibilidad, que expone el texto de notas,
tablas y documentos del tablero. Las imágenes y archivos adjuntos no se han
copiado al repositorio salvo que se indique.

## Qué se ha incorporado

| Dato | Origen | Destino |
| --- | --- | --- |
| Equipo: Antonio, Carla, Fausto, Juan, Marianna | Canva diapositiva 2 | `README.md`, `surge-website` (equipo) |
| Modelo B2C/D2C y reparto 60 % físico / 40 % online | Miro «Modelo de negocio» | `analisis-interno/4ps/punto-de-venta.md` |
| Piloto de 3.000 latas, 1.000 por sabor | Miro «Modelo de negocio» | Ya estaba en `producto.md`; se refuerza en `punto-de-venta.md` |
| Prospectos de gimnasios, cafeterías y tiendas | Miro «Punto de venta» | `analisis-interno/4ps/punto-de-venta.md` |
| Precio online 24 latas: 59,90 € compra única / 49,90 € suscripción | Miro «Precios» | `analisis-interno/4ps/precio.md` |
| Precio local 3,50–3,80 €; coste variable 0,65 €; 3.000 latas/mes | Miro «Facturación estimada» | `analisis-interno/4ps/precio.md` |
| Facturación 7.500 €/mes, 90.000 €/año, 3.550 €/mes antes de impuestos | Miro «Facturación estimada» | `analisis-interno/4ps/precio.md` |
| Campaña Bestial Race: equipos, influencers y gymkana | Canva diapositiva 44 y Miro | `promocion.md`, `slides/40`, `surge-website` |
| Calendario de campaña mayo–julio | Brief de Bestial Race y Miro | `slides/53`, `surge-website` |
| Presupuesto anual de 50.000 € | Canva diapositiva 57 | `slides/51`, `precio.md` |
| Nombre «SURGE Club» para fidelización | Canva diapositiva 9 y Miro | `promocion.md`, `surge-website` |
| Hashtag #SurgeCanarias | Canva diapositiva 52 | `surge-website` |
| 9 influencers de la campaña Bestial Race | Brief de Bestial Race y Miro | `slides/40`, `surge-website` |

## Conflictos detectados

Estos datos no se han aplicado sin más: se documentan para que el equipo decida.

| Tema | Canva | Miro / repositorio | Decisión aplicada |
| --- | --- | --- | --- |
| Unidades del piloto | 6.000 unidades (diapositiva 6) | 3.000 latas, 1.000 por sabor | Se mantienen 3.000. Canva parece una versión anterior o un error. |
| Precio individual | 2,50–3,00 € (diapositivas 6 y 9) | 1,95 € en `precio.md`; la web usa 2,08–2,15 €/lata en packs | No se cambia el precio de la web. Se añade el modelo de 24 latas a `precio.md` y se marca el conflicto. |
| Suscripción | 24 latas: 49,90 €/mes | `precio.md` tenía 12 latas: 22,90 € | Se añade el modelo de 24 latas como modelo web; el de 12 latas queda como alternativa. |
| IGIC | — | Miro: 15 % para bebidas de más de 150 mg/l | Se marca `[SUPUESTO: verificar]`. No se usa en la web. |
| Producto | Flama, Mentisimo y Cocus | Miro contiene una línea alternativa «ELEMENTS» (coco + jengibre, ginseng + matcha, guaraná + berry) | Se descarta. No es la formulación vigente. |
| Claims | — | Miro: «sin efecto bajón», «efecto saciante», «sostenible», «para todo el público» | No se usan. Ya están prohibidos en `propuesta-de-valor.md` y `producto.md`. |

## Contenido descartado o pendiente

- **Línea ELEMENTS:** fórmula alternativa del tablero Miro. No se incorpora.
- **Fecha 15 de noviembre de 2025:** aparece en una ilustración antigua de Bestial
  Race. No se usa como fecha actual.
- **Tabla de 20 palabras clave SEO:** está en el archivo
  `SURGE_Plan_SEO_Keywords_Diapositiva_43(1).pptx`, dentro del tablero Miro. No se
  ha podido descargar desde la vista pública. `slides/44` queda con candidatas y
  con la nota de que los volúmenes deben salir de ese archivo.
- **Capturas, moodboards y documentos PDF:** se han revisado como referencia,
  pero no se copian al repositorio. Los assets de la web siguen siendo los del
  repositorio.
- **Nombres antiguos:** el Miro mezcla nombres del relato fundacional (Pablo,
  Faus, Juan Antonio) con el equipo actual. Se usa el equipo del README: Juan,
  Antonio, Carla, Marianna y Fausto.

## Cómo se ha extraído

- Canva: presentación a pantalla completa y lectura del texto de cada diapositiva.
- Miro: botón «Mejorar la accesibilidad» y lectura del esquema de solo lectura.
- No se ha usado ninguna API privada ni se han copiado archivos con derechos de
  terceros.

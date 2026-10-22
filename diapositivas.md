# Diapositivas del plan de marketing (Canva)

Mapa completo de la presentación de Surge: qué hay hoy en cada diapositiva,
qué información falta y qué hace falta para darla por terminada.

- **TLDR 1** — La presentación tiene 54 diapositivas y está construida sobre una
  plantilla de curso: portada, 7 secciones y fichas con texto de relleno
  («Lorem ipsum») o instrucciones del profesor. Ninguna ficha tiene todavía
  contenido de Surge.
- **TLDR 2** — Sólo 4 diapositivas son tablas vacías con estructura útil
  (4Ps, email marketing, SEO, SEM); el resto son título + párrafo libre.
- **TLDR 3** — Para completarla hacen falta datos que aún no están en el
  repositorio (precio, riesgos, tamaño de mercado, presupuesto propio). Están
  marcados como `[SUPUESTO]` o `[PENDIENTE]` en cada ficha.

---

## 1. Cómo usar este archivo

Cada ficha describe una diapositiva con este orden fijo y vive en su propio
archivo dentro de `slides/`, con el nombre `NN-titulo.md` (por ejemplo,
`slides/08-marketing-mix-4ps.md`). Este documento es el mapa y el índice; el
detalle de cada diapositiva está en su archivo.

| Campo | Para qué sirve |
| --- | --- |
| **Sección / Tipo** | Dónde cae en la barra de secciones y qué layout usa |
| **Texto actual** | Lo que hay escrito hoy, literal. Es el punto de partida, no una propuesta |
| **Para completarla** | Lista de acciones concretas para cerrar la diapositiva |
| **Fuente en el repo** | Archivo del que sale el contenido, o `—` si no existe |
| **Criterio de cierre** | Cómo saber que está terminada sin discutirlo |
| **Aviso** | Filtro legal, nutricional o de datos, sólo cuando aplica |

Regla de trabajo: si un dato no está en el repositorio, no se escribe en la
diapositiva. Se marca `[PENDIENTE: quién lo aporta]` y se deja la diapositiva
abierta.

---

## 2. Ficha técnica del archivo

| Campo | Valor |
| --- | --- |
| URL | https://www.canva.com/design/DAHX4LWHQlM/hEu72-4TUZVbMyaAfDh3SQ |
| Diapositivas | 54 |
| Formato | 16:9 |
| Plantilla | «Plan de Marketing», Curso de Marketing Digital con IA (v.2026) |
| Barra de secciones | 7 pestañas fijas en la parte inferior |
| Color de acento de la plantilla | `#54979B` (cian apagado, muestreado del archivo) |
| Estado | Estructura completa, contenido por escribir |
| Última lectura | 21 de octubre de 2026 |

Nota de color: el acento `#54979B` de la plantilla **no** está en la paleta de
`branding.md` (`#2d6a4f`, `#b7e4c7`, `#f4d35e`, `#fefae0`, `#3d2b1f`). Hay que
decidir si se sustituye el cian por el verde de marca o se mantiene la plantilla
tal cual. Ver sección 7.

---

## 3. Reglas globales de la presentación

- **Idioma:** español. Sin emojis. Sin adjetivos vacíos.
- **Cifras:** toda cifra lleva fuente o etiqueta `[SUPUESTO]`.
- **Tono:** 40/60 seria/divertida, 90/10 amigable/autoritaria, 10/90 élites/masas.
  El 10% autoritario se reserva para composición y salud, siempre con fuente.
- **Legal:** Reglamento (CE) 1924/2006 para cualquier declaración de salud o
  nutricional; Directiva (UE) 2024/825 para cualquier alegación ambiental.
  «Natural», «saludable», «sin efectos adversos» y «ecológico» no se escriben
  sin prueba o sin reformulación.
- **Datos de terceros:** el DAFO de Zara de la diapositiva 32 es material del
  curso. No se reutiliza como análisis propio.

---

## 4. Mapa de secciones

| # | Sección | Diapositivas | Estado |
| --- | --- | --- | --- |
| 1 | Portada y equipo | 1–2 | Estructura lista, falta contenido |
| 2 | Análisis interno | 3–12 | Texto de relleno |
| 3 | Análisis externo | 13–17 | Texto de relleno + 1 mapa vacío |
| 4 | Análisis marketing (situación actual) | 18–30 | Tablas vacías + instrucciones |
| 5 | DAFO | 31–33 | Ejemplo del curso + ficha vacía |
| 6 | Plan de acción: objetivos | 34–36 | Estructura lista |
| 7 | Plan de acción: estrategias y acciones | 37–49 | Títulos e instrucciones |
| 8 | Plan de acción: presupuesto | 50–51 | Cifra del curso |
| 9 | Plan de acción: cronograma | 52–53 | Vacío |
| 10 | Cierre | 54 | Estructura lista |

Las pestañas de la barra inferior agrupan estas secciones en 7 bloques:
Análisis interno · Análisis externo · Análisis MK · Objetivos · Estrategias +
acciones · Presupuesto · Cronograma.

---

## 5. Fichas por diapositiva

Cada diapositiva tiene su ficha completa en `slides/`, un archivo por
diapositiva. Esta tabla es sólo el índice: el detalle vive en el enlace.

| # | Diapositiva | Sección | Ficha |
| --- | --- | --- | --- |
| 01 | Portada | ninguna (sin barra) | [01-portada.md](slides/01-portada.md) |
| 02 | Equipo | ninguna | [02-equipo.md](slides/02-equipo.md) |
| 03 | Separador «Análisis» | — | [03-separador-analisis.md](slides/03-separador-analisis.md) |
| 04 | Separador «Análisis interno» | — | [04-separador-analisis-interno.md](slides/04-separador-analisis-interno.md) |
| 05 | Sobre la empresa: historia y modelo de negocio | Análisis interno | [05-sobre-la-empresa-historia-y-modelo-de-negocio.md](slides/05-sobre-la-empresa-historia-y-modelo-de-negocio.md) |
| 06 | Sobre la empresa: misión, visión y valores | Análisis interno | [06-sobre-la-empresa-mision-vision-y-valores.md](slides/06-sobre-la-empresa-mision-vision-y-valores.md) |
| 07 | Sobre la empresa: propuesta de valor | Análisis interno | [07-sobre-la-empresa-propuesta-de-valor.md](slides/07-sobre-la-empresa-propuesta-de-valor.md) |
| 08 | Marketing mix (4Ps) | Análisis interno | [08-marketing-mix-4ps.md](slides/08-marketing-mix-4ps.md) |
| 09 | Público objetivo | Análisis interno | [09-publico-objetivo.md](slides/09-publico-objetivo.md) |
| 10 | Buyer persona 1 | Análisis interno | [10-buyer-persona-1.md](slides/10-buyer-persona-1.md) |
| 11 | Buyer persona 2 | Análisis interno | [11-buyer-persona-2.md](slides/11-buyer-persona-2.md) |
| 12 | Buyer persona 3 | Análisis interno | [12-buyer-persona-3.md](slides/12-buyer-persona-3.md) |
| 13 | Separador «Análisis externo» | — | [13-separador-analisis-externo.md](slides/13-separador-analisis-externo.md) |
| 14 | Mercado | Análisis externo | [14-mercado.md](slides/14-mercado.md) |
| 15 | Sector | Análisis externo | [15-sector.md](slides/15-sector.md) |
| 16 | Competidores | Análisis externo | [16-competidores.md](slides/16-competidores.md) |
| 17 | Mapa de posicionamiento | Análisis externo | [17-mapa-de-posicionamiento.md](slides/17-mapa-de-posicionamiento.md) |
| 18 | Separador «Análisis Marketing \| Situación actual» | — | [18-separador-analisis-marketing-situacion-actual.md](slides/18-separador-analisis-marketing-situacion-actual.md) |
| 19 | Email marketing: análisis interno y externo | Análisis MK | [19-email-marketing-analisis-interno-y-externo.md](slides/19-email-marketing-analisis-interno-y-externo.md) |
| 20 | Email marketing: capturas | Análisis MK | [20-email-marketing-capturas.md](slides/20-email-marketing-capturas.md) |
| 21 | RRSS: buenas prácticas propias | Análisis MK | [21-rrss-buenas-practicas-propias.md](slides/21-rrss-buenas-practicas-propias.md) |
| 22 | RRSS: buenas prácticas de competidores | Análisis MK | [22-rrss-buenas-practicas-de-competidores.md](slides/22-rrss-buenas-practicas-de-competidores.md) |
| 23 | RRSS: aspectos a mejorar (propios) | Análisis MK | [23-rrss-aspectos-a-mejorar-propios.md](slides/23-rrss-aspectos-a-mejorar-propios.md) |
| 24 | RRSS: análisis cuantitativo | Análisis MK | [24-rrss-analisis-cuantitativo.md](slides/24-rrss-analisis-cuantitativo.md) |
| 25 | Web y landings (situación actual) | Análisis MK | [25-web-y-landings-situacion-actual.md](slides/25-web-y-landings-situacion-actual.md) |
| 26 | SEO: buenas prácticas | Análisis MK | [26-seo-buenas-practicas.md](slides/26-seo-buenas-practicas.md) |
| 27 | SEO: aspectos a mejorar | Análisis MK | [27-seo-aspectos-a-mejorar.md](slides/27-seo-aspectos-a-mejorar.md) |
| 28 | SEO: análisis comparativo | Análisis MK | [28-seo-analisis-comparativo.md](slides/28-seo-analisis-comparativo.md) |
| 29 | SEM: análisis de competidores | Análisis MK | [29-sem-analisis-de-competidores.md](slides/29-sem-analisis-de-competidores.md) |
| 30 | SEM: capturas y notas | Análisis MK | [30-sem-capturas-y-notas.md](slides/30-sem-capturas-y-notas.md) |
| 31 | Separador «Análisis DAFO» | — | [31-separador-analisis-dafo.md](slides/31-separador-analisis-dafo.md) |
| 32 | DAFO: ejemplo (Zara) | Análisis MK | [32-dafo-ejemplo-zara.md](slides/32-dafo-ejemplo-zara.md) |
| 33 | DAFO de Surge | Análisis MK | [33-dafo-de-surge.md](slides/33-dafo-de-surge.md) |
| 34 | Separador «Plan de acción» | — | [34-separador-plan-de-accion.md](slides/34-separador-plan-de-accion.md) |
| 35 | Separador «Plan de acción \| Objetivos» | — | [35-separador-plan-de-accion-objetivos.md](slides/35-separador-plan-de-accion-objetivos.md) |
| 36 | Objetivos SMART | Objetivos | [36-objetivos-smart.md](slides/36-objetivos-smart.md) |
| 37 | Separador «Estrategias y acciones» | — | [37-separador-estrategias-y-acciones.md](slides/37-separador-estrategias-y-acciones.md) |
| 38 | Email marketing: acciones | Estrategias + acciones | [38-email-marketing-acciones.md](slides/38-email-marketing-acciones.md) |
| 39 | RRSS: mejoras propuestas | Estrategias + acciones | [39-rrss-mejoras-propuestas.md](slides/39-rrss-mejoras-propuestas.md) |
| 40 | RRSS: acciones con influencers | Estrategias + acciones | [40-rrss-acciones-con-influencers.md](slides/40-rrss-acciones-con-influencers.md) |
| 41 | RRSS: sorteo | Estrategias + acciones | [41-rrss-sorteo.md](slides/41-rrss-sorteo.md) |
| 42 | RRSS: crisis de reputación | Estrategias + acciones | [42-rrss-crisis-de-reputacion.md](slides/42-rrss-crisis-de-reputacion.md) |
| 43 | Web y landings: acciones | Estrategias + acciones | [43-web-y-landings-acciones.md](slides/43-web-y-landings-acciones.md) |
| 44 | SEO: palabras clave | Estrategias + acciones | [44-seo-palabras-clave.md](slides/44-seo-palabras-clave.md) |
| 45 | SEO: On Page | Estrategias + acciones | [45-seo-on-page.md](slides/45-seo-on-page.md) |
| 46 | SEO: Off Page | Estrategias + acciones | [46-seo-off-page.md](slides/46-seo-off-page.md) |
| 47 | SEO: calendario de contenidos del blog | Estrategias + acciones | [47-seo-calendario-de-contenidos-del-blog.md](slides/47-seo-calendario-de-contenidos-del-blog.md) |
| 48 | SEM: calendario de campañas | Estrategias + acciones | [48-sem-calendario-de-campanas.md](slides/48-sem-calendario-de-campanas.md) |
| 49 | SEM: tipos de campañas | Estrategias + acciones | [49-sem-tipos-de-campanas.md](slides/49-sem-tipos-de-campanas.md) |
| 50 | Separador «Plan de acción \| Presupuesto» | — | [50-separador-plan-de-accion-presupuesto.md](slides/50-separador-plan-de-accion-presupuesto.md) |
| 51 | Presupuesto | Presupuesto | [51-presupuesto.md](slides/51-presupuesto.md) |
| 52 | Separador «Plan de acción \| Cronograma» | — | [52-separador-plan-de-accion-cronograma.md](slides/52-separador-plan-de-accion-cronograma.md) |
| 53 | Cronograma de acciones | Cronograma | [53-cronograma-de-acciones.md](slides/53-cronograma-de-acciones.md) |
| 54 | Cierre | — | [54-cierre.md](slides/54-cierre.md) |

---

## 6. Lo que falta en el repositorio para poder rellenar todo

| Dato | Diapositivas afectadas | Archivo que debería tenerlo | Estado |
| --- | --- | --- | --- |
| PVP, margen y precio de suscripción | 8, 17, 48 | `analisis-interno/4ps/precio.md` | PVP y packs definidos; falta escandallo |
| Receta por lata, COGS y LCA | 8, 17, 51 | `analisis-interno/4ps/producto.md`, `.../precio.md` | Receta definida; faltan cotizaciones y LCA |
| Definición explícita del público | 9, 10–12 | `target.md` | Contiene distribución, no público |
| Tamaño y crecimiento del mercado | 14, 16 | — | No existe |
| Buyer personas | 10–12 | — | No existen |
| Métricas de RRSS | 24, 41 | `metrics.md` | Hay métricas de negocio y sostenibilidad; faltan RRSS |
| Presupuesto y reparto por partida | 48, 51 | `producto.md`, `precio.md` | 50.000 € con reparto `[SUPUESTO]`; falta confirmar |
| Registro de riesgos | 33 | `risks.md` | Vacío |
| Web y landings | 25, 43 | — | No existen |
| Datos SEO y SEM de competidores | 28, 29, 30 | — | No existen |

---

## 7. Decisiones pendientes del equipo

| Decisión | Por qué bloquea | Responsable propuesto |
| --- | --- | --- |
| Acento de color: `#54979B` de la plantilla o `#2d6a4f` de marca | Afecta a las 54 diapositivas | Marca |
| Mantener o retirar la franja de logotipos institucionales | Obligaciones de publicidad de ayudas | Juan |
| Cifra de presupuesto: 50.000€ del curso o presupuesto real | Condiciona SEM, muestras e influencers | Antonio |
| Ejes del mapa de posicionamiento (precio/calidad o natural/convencional) | Sin precio no hay eje vertical defendible | Carla |
| Número de buyer personas: 3 o 2 | Mejor dos reales que tres inventadas | Marianna |
| Mantener el DAFO de Zara como ejemplo | En una entrega externa sobra | Fausto |

---

## 8. Convenciones de este archivo

- `[SUPUESTO]`: cifra o afirmación sin fuente que hay que validar antes de publicar.
- `[PENDIENTE: quién]`: hueco que necesita un dato que nadie ha aportado todavía.
- «Texto actual» es literal: describe la plantilla, no una propuesta de copy.
- Las cifras de esta presentación se leen como proporciones A/B cuando son
  patrones de comunicación (ver `config/communication.md`); en el resto de casos
  son datos y necesitan fuente.

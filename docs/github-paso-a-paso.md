# GitHub paso a paso

Guía para quien no ha usado GitHub nunca. No hace falta instalar nada: todo se
hace desde el navegador, en github.com.

Si te pierdes, vuelve a esta idea: **tu trabajo no se pierde nunca**. Cada versión
del archivo queda guardada y se puede recuperar.

> ¿Solo quieres leer o descargar los documentos? No necesitas esta guía. Mira
> [`descargar-los-archivos.md`](descargar-los-archivos.md).

---

## Antes de empezar

Necesitas dos cosas:

1. Una cuenta de GitHub (gratis, en github.com).
2. Que alguien del equipo te invite al repositorio de Surge.

Cuando aceptes la invitación, verás el repositorio y sus archivos, todos acabados
en `.md`. Esos archivos son documentos de texto normales.

---

## Cambiar un texto que ya existe

**Paso 1.** Abre el archivo que quieres cambiar, por ejemplo `metrics.md`.

**Paso 2.** Arriba a la derecha del documento verás un **lápiz**. Púlsalo. Si no
lo ves, es que no tienes permiso de escritura: pide que te inviten.

**Paso 3.** Se abre un editor con el texto. Escribe tus cambios como en cualquier
documento.

**Paso 4.** Baja hasta abajo del todo. Verás un cuadro que dice *Commit changes*
y otro que dice *Extended description*.

- En el primero, escribe **qué** has cambiado y **por qué**, en una frase:
  `branding: cambio el eslogan por la versión aprobada en la reunión`.
- En el segundo, si quieres, añade más detalle.

**Paso 5.** Justo debajo, elige esta opción:

> Create a new branch for this commit and start a pull request

Es la opción que **no** toca la versión oficial. La otra, «commit directly to the
main branch», la escribimos y la borramos sin usar nunca.

**Paso 6.** Pulsa el botón verde **Propose changes**.

**Paso 7.** Se abre una pantalla nueva. Pon un título corto, explica en el cuadro
grande por qué haces este cambio, y pulsa **Create pull request**.

**Paso 8.** Avisa a alguien del equipo. Tu cambio está propuesto, no aplicado.

---

## Crear un archivo nuevo

Mismo proceso, pero en lugar del lápiz:

1. Entra en la carpeta donde quieres el archivo (`analisis-interno/4ps/`, por ejemplo).
2. Pulsa **Add file** → **Create new file**.
3. Escribe el nombre terminado en `.md`, por ejemplo `distribucion.md`.
4. Escribe el contenido.
5. Sigue los pasos 4 a 8 del apartado anterior.

Un nombre que empiece por mayúscula o lleve espacios dará problemas más adelante.
Usa minúsculas y guiones: `plan-de-verano.md`.

---

## Cómo escribir en estos archivos

Los archivos terminan en `.md`, que significa *markdown*. Es texto normal con
cuatro trucos:

| Quiero | Escribo | Se ve |
|---|---|---|
| Un título | `# Precio` | Precio (grande) |
| Un subtítulo | `## Detalle` | Detalle (mediano) |
| Una lista | `- primer punto` | una viñeta |
| Una lista numerada | `1. primer paso` | un paso numerado |
| Negrita | `**importante**` | **importante** |
| Una tabla | `\| A \| B \|` | una tabla |

Pulsa la pestaña **Preview** arriba del editor para ver cómo queda antes de guardar.
Si algo sale raro, tranquilo: se puede corregir después.

---

## Revisar el cambio de otra persona

Cuando alguien te pida revisión:

1. Abre la pestaña **Pull requests** del repositorio y entra en la que te toca.
2. Pulsa **Files changed**. Verás en verde lo que se añade y en rojo lo que se quita.
3. Léelo entero. Si algo no te convence, pon el cursor en esa línea, escribe el
   comentario y pulsa **Start a review**, y luego **Comment**.
4. Si todo está bien, pulsa **Review changes** → **Approve**, y después
   **Merge pull request**.

Tres preguntas antes de aprobar:

- ¿Se entiende sin haber estado en la conversación donde se decidió?
- ¿Contradice algo de `branding.md` o de `challenges.md`?
- ¿Las cifras llevan fuente o están marcadas como `[SUPUESTO]`?

Aprobar no es un trámite: es tu firma. Si algo no lo entiendes, pide que te lo
expliquen en lugar de aprobarlo.

---

## Cuando alguien revisa tu cambio

Pueden pasar tres cosas:

- **Te aprueban y lo integran.** Ya está, tu texto es la versión oficial.
- **Te piden cambios.** Verás comentarios en la conversación. Vuelve a la rama
  (pestaña *Pull requests*, tu propuesta, pestaña *Files changed*), pulsa el lápiz
  otra vez, corrige y guarda. La propuesta se actualiza sola.
- **Nadie contesta.** Insiste por el grupo de siempre. Una propuesta parada es
  trabajo invisible.

---

## Cómo deshacer

**Si no te gusta algo que has escrito y aún no está aprobado:** abre el archivo en
tu rama, pulsa el lápiz y déjalo como estaba. Guarda y ya está.

**Si el cambio ya se aprobó y quieres deshacerlo:** no borres nada a mano. Abre la
propuesta que se aprobó, busca el botón **Revert** y pulsa. GitHub propone el
cambio inverso, que otra persona revisa y aprueba igual que cualquier otro.

**Si escribiste por error directamente en la versión oficial:** avisa en el grupo.
Se revierte en dos minutos. No pasa nada, pero mejor que lo sepa alguien antes de
que el resto siga trabajando sobre el error.

**Si borraste un archivo sin querer:** también tiene botón **Revert**. Y aunque no
lo hubiera, la versión anterior siempre sigue guardada en el historial.

---

## Cinco palabras que verás todo el rato

- **Repositorio**: la carpeta del proyecto, con todo el historial.
- **Rama** (*branch*): una copia paralela donde trabajas sin molestar a nadie.
- **Commit**: el guardado de un cambio, con su explicación.
- **Pull request**: la petición de incorporar tu trabajo a la versión oficial.
- **Merge**: el momento en que tu trabajo se une a la versión oficial.

Están explicadas con más detalle en [`glosario.md`](glosario.md).

---

## Y si odias que esto sea tan pesado

Es un paso extra por cada cambio. A cambio: nada se pierde, se sabe quién cambió
qué y cuándo, y dos personas no pueden pisarse el trabajo sin darse cuenta. Para
un plan que vamos a estar tocando durante meses entre cinco, merece la pena.

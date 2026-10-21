# Surge — Plan de Marketing

Este repositorio es el plan de marketing de **Surge**, una bebida energética natural.
Aquí escribimos entre cinco: Juan, Antonio, Carla, Marianna y Fausto.

Si nunca has usado GitHub, no pasa nada. No hace falta instalar nada ni saber
programar. Todo se hace desde el navegador, como si fuera un Google Docs que
guarda el historial de todos los cambios.

---

## Lo primero: por qué funciona así

En un documento compartido normal, cualquiera puede borrar el trabajo de otro sin
que nadie se entere. Aquí no.

En este repositorio hay dos versiones de cada documento:

| Versión | Qué es | Quién puede escribir |
|---|---|---|
| `main` | La versión buena, la oficial | Nadie directamente |
| Tu rama | Tu copia de trabajo | Solo tú |

Cuando quieres añadir o cambiar algo, lo haces en tu copia y luego pides que se
incorpore a la versión buena. Esa petición se llama **pull request** (o
«propuesta»). Otra persona la lee, la aprueba, y entonces el cambio entra.

Ventajas: nada se pierde, todo queda registrado y nadie pisa el trabajo de otro.
El coste es un solo paso extra: pedir que te lo revisen.

---

## Las tres reglas de oro

1. **Un cambio, una propuesta.** No mezcles «arreglar el precio» con «reescribir
   el eslogan» en la misma petición. Es más fácil de revisar y de deshacer.
2. **Nunca escribas directamente en la versión oficial.** Si ves un botón que
   dice «commit directly to the main branch», no lo uses.
3. **Si dudas, pregunta.** Antes de borrar un archivo o cambiar algo de otra
   persona, coméntalo. Preguntar cuesta un minuto; recuperar algo borrado, a veces no.

---

## Cómo cambiar un texto en tres minutos

1. Entra en GitHub y abre el archivo que quieres cambiar.
2. Pulsa el **lápiz** (arriba a la derecha del documento). Se abre un editor.
3. Escribe tus cambios.
4. Baja abajo del todo. En el cuadro de texto escribe **qué has cambiado**, en una
   frase: `precio: añado el rango 2,50-3 €`.
5. Elige **Create a new branch for this commit and start a pull request** y pulsa
   el botón verde.
6. Rellena el título, explica brevemente por qué, y pulsa **Create pull request**.
7. Avisa a alguien del equipo para que lo revise.

Ya está. No has tocado la versión oficial, no has roto nada y puedes deshacerlo
en cualquier momento.

Guía detallada, con qué hacer si algo sale mal:
[`docs/github-paso-a-paso.md`](docs/github-paso-a-paso.md)

---

## Cómo se revisa una propuesta

Si alguien te pide que revises la suya:

1. Abre la pestaña **Pull requests** y entra en la que te toque.
2. Pulsa **Files changed**: verás en verde lo que se añade y en rojo lo que se quita.
3. Si algo no te convence, escribe un comentario y pulsa **Comment**.
4. Si todo está bien, pulsa **Approve** y después **Merge pull request**.

Aprobar no es un trámite: es tu firma. Si no entiendes un cambio, pide que te lo
expliquen en lugar de aprobarlo.

### Los formularios ya están puestos

Cuando abras una propuesta o una incidencia, GitHub te mostrará un formulario con
las preguntas ya escritas. Solo tienes que rellenarlo. Hay tres para incidencias:

| Elige | Cuándo |
|---|---|
| **Tengo una idea** | Propones algo nuevo o mejoras lo que hay |
| **Algo está mal** | Un error, un hueco, un dato que no cuadra |
| **Hay que decidir algo** | Una decisión abierta que necesita al equipo |

No hace falta rellenar todo. Si un apartado no aplica, déjalo vacío o escribe «no
lo sé». Un hueco honesto es mejor que un dato inventado.

---

## Qué hay en este repositorio

| Archivo | De qué va | Estado |
|---|---|---|
| `goal.md` | Qué queremos conseguir | Listo |
| `origin.md` | De dónde nace Surge, contado por nosotros | Listo |
| `branding.md` | Nombre, eslogan, valores, colores, tono | Listo |
| `target.md` | Dónde y cómo vamos a distribuir | Listo |
| `references.md` | Competencia que miramos | Listo |
| `challenges.md` | Los obstáculos, incluidos los legales | Listo |
| `metrics.md` | Cómo medimos si funciona | Listo |
| `risks.md` | Qué puede salir mal | **Vacío, falta escribirlo** |
| `analisis-interno/propuesta-de-valor.md` | Qué aportamos que no aporten otros | Listo |
| `analisis-interno/4ps/producto.md` | Las tres bebidas y sus sabores | En progreso |
| `analisis-interno/4ps/precio.md` | Cuánto cuesta y por cuánto se vende | **Vacío, falta escribirlo** |
| `analisis-interno/4ps/punto-de-venta.md` | Dónde se vende | En progreso |
| `analisis-interno/4ps/promocion.md` | Degustaciones, redes, fidelización | En progreso |
| `config/` | Instrucciones para el asistente de IA | No tocar |
| `docs/` | Ayuda para usar GitHub | No tocar |

Los archivos en negrita están vacíos. Si tu tarea depende de ellos, mejor
escribirlos antes que improvisar.

---

## Cómo escribimos

Las reglas de idioma, tono y formato están en [`config/`](config/). Resumen:

- Todo en **español**.
- Los documentos empiezan con un **resumen corto** de lo esencial.
- **Sin emojis** y sin adjetivos vacíos («increíble», «revolucionario»).
- Toda cifra lleva **fuente**, o se marca como suposición.

---

## Ayuda

- No sé qué es una pull request → [`docs/github-paso-a-paso.md`](docs/github-paso-a-paso.md)
- No entiendo una palabra → [`docs/glosario.md`](docs/glosario.md)
- No sé dónde va mi idea → [`docs/mapa-del-proyecto.md`](docs/mapa-del-proyecto.md)
- He roto algo → [`docs/github-paso-a-paso.md`](docs/github-paso-a-paso.md), apartado
  «Cómo deshacer»

---

## Para quien administra el repositorio

Antes de invitar al equipo, activa estas dos protecciones en GitHub:

1. **Settings → Branches → Add branch protection rule** sobre `main`, con
   *Require a pull request before merging* y al menos **1 aprobación**.
2. **Settings → General → Pull requests**, marca *Allow auto-merge* si quieres que
   los cambios aprobados se integren solos.

Sin la primera, la regla de oro número dos es solo una sugerencia amable.

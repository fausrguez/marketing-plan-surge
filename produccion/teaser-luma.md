# Teaser de Surge — prompts para Luma

Producción del teaser corporativo de 24 segundos. Este archivo contiene los
prompts de Luma (Dream Machine), los fotogramas de entrada y salida, las
transiciones y las reglas de continuidad.

- **Duración:** 24 s.
- **Formato:** 16:9, 24 fps. Conformar a 25 fps si el proyecto lo pide.
- **Voz en off:** aprobada; se añade en postproducción.
- **Estado:** listo para generar placas. Etiqueta, logo, tipografía y aviso legal
  se componen en postproducción.
- **Fecha:** 21 de octubre de 2026.

## 1. Cómo usar este archivo

1. Luma genera clips de 5 o 9 segundos. No le pases los 24 segundos en un solo
   prompt: genera un clip por escena y monta después.
2. Pega el **prompt maestro** al inicio de cada escena, o úsalo como bloque de
   estilo si la interfaz separa “prompt” y “style”.
3. Añade el **negative prompt** en todas las generaciones. Si no hay campo
   aparte, termina el prompt con `Avoid: ...`.
4. Genera a 5 s y recorta en montaje. La escena 3 son tres clips, no uno de 7 s.
5. Usa la misma imagen de referencia de las tres latas en todas las escenas. Si
   la interfaz permite `seed`, repite la misma semilla.
6. No pidas a Luma que genere el logo, la tipografía, la receta ni el aviso
   legal. Sale deformado. Se compone en postproducción.

## 2. Resumen de escenas

| Escena | Timecode final | Clip Luma | Recorte |
| --- | --- | --- | --- |
| 1. El corte | 00:00–00:03 | 5 s | 3 s |
| 2. La espiral | 00:03–00:06 | 5 s | 3 s |
| 3A. Flama | 00:06–00:08,3 | 5 s | 2,3 s |
| 3B. Mentisimo | 00:08,3–00:10,6 | 5 s | 2,3 s |
| 3C. Cocus | 00:10,6–00:13 | 5 s | 2,4 s |
| 4. La fórmula | 00:13–00:18 | 5 s | 5 s |
| 5. La receta | 00:18–00:21 | 5 s | 3 s |
| 6. Cierre | 00:21–00:24 | 5 s | 3 s |

## 3. Prompt maestro

Pégalo al inicio de cada escena.

```text
Cinematic premium beverage commercial. Matte aluminum 330 ml cans with paper labels. Cream, deep green, deep red and ocean blue palette. Soft directional light from the left, subtle rim light on the aluminum, shallow depth of field, natural textures, editorial still life, calm and tactile. Consistent can proportions and label colors across all shots. No glossy plastic, no neon, no futuristic effects. No text, no readable letters, no distorted logos, no watermarks, no extra cans, no brand logos on clothing or props. 16:9, 24 fps.
```

## 4. Negative prompt

Úsalo en todas las generaciones.

```text
text, letters, numbers, watermark, logo distortion, extra cans, deformed cans, melting aluminum, plastic-looking cans, extra fingers, deformed hands, rings, jewelry, watches, brand logos on clothing, neon lights, lens flare, flicker, morphing, duplicate products, low resolution, oversaturated colors, cartoon, CGI look.
```

## 5. Escena 1 — El corte

**Timecode final:** 00:00–00:03.
**Duración Luma:** 5 s. **Recorte:** 3 s.

**Fotograma inicial:** macro de la lata roja, etiqueta centrada, espiral de crema
visible.
**Fotograma final:** el papel crema llena el encuadre.

```text
Extreme macro product shot of one matte aluminum 330 ml can with a deep red paper label and a subtle yellow flame pattern, standing on a cream seamless surface. The can rotates slowly clockwise on a turntable and stops with the label centered. A soft directional light from the left reveals a subtle cream spiral mark printed on the label; the mark moves with the can and never changes shape. Camera: 100 mm macro lens, f/5.6, at label height, 90 degrees to the can, slow dolly in until the cream paper fills the frame. Calm, premium, tactile, natural aluminum texture, subtle rim light on the right edge. No text, no letters, no extra objects. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Dolly in`, intensidad baja.

**Nota:** el giro de la lata debe ser lento. Si Luma deforma la etiqueta al girar,
genera la lata estática y anima solo el `dolly in`. El logo de las latas es crema,
no verde: el `match cut` de salida se hace sobre el crema de la etiqueta.

## 6. Escena 2 — La espiral

**Timecode final:** 00:03–00:06.
**Duración Luma:** 5 s. **Recorte:** 3 s.

**Fotograma inicial:** superficie crema, sin latas.
**Fotograma final:** las tres latas alineadas, etiquetas hacia cámara.

```text
Wide product shot of three matte aluminum 330 ml cans on a cream seamless set, evenly spaced left to right: a deep red label with a subtle yellow flame pattern, a deep green label with a subtle mint leaf pattern, and an ocean blue label with a subtle ice crystal pattern. Behind them, a large minimal dark green spiral mark is printed on the cream backdrop. The camera starts tight on a cream surface, then pulls back slowly to reveal the spiral and the three cans. Soft directional light from the left, subtle rim light on the aluminum, premium editorial still life, symmetrical composition, shallow depth of field. Cans upright, labels facing camera. No hands, no text, no letters, no extra objects. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Dolly out`, intensidad media.

**Nota:** el `whip pan` final hacia Flama no se genera aquí. Se hace en montaje con
un giro de 2 fotogramas y un fundido al rojo `#b23a2b`. Si se genera en Luma, sale
una transición incontrolada.

## 7. Escena 3A — Flama

**Timecode final:** 00:06–00:08,3.
**Duración Luma:** 5 s. **Recorte:** 2,3 s.

**Fotograma inicial:** banco de box vacío.
**Fotograma final:** lata roja centrada, etiqueta hacia cámara.

```text
Low-angle product shot in a clean gym box. A hand in a neutral sleeve enters from the right holding a matte aluminum 330 ml can with a deep red paper label and a subtle yellow flame pattern, and places it on a dark wooden bench in the center of the frame, label facing camera. Camera: 35 mm lens, f/2.8, 25 cm above the floor, slow tilt up and a slight push in. Soft directional light from the left, chalk dust in the air, warm neutral grade, shallow depth of field. No face, no gym brand logos, no text on the can, no extra equipment. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Tilt up` + `Dolly in`, intensidad baja.

**Nota:** Luma deforma manos con frecuencia. Si sale mal, genera el plano sin mano
y añade la mano en rodaje real o en postproducción.

## 8. Escena 3B — Mentisimo

**Timecode final:** 00:08,3–00:10,6.
**Duración Luma:** 5 s. **Recorte:** 2,3 s.

**Fotograma inicial:** escritorio despejado.
**Fotograma final:** lata verde centrada, etiqueta hacia cámara.

```text
Eye-level product shot in a bright coworking space. A hand in a neutral sleeve enters from the right holding a matte aluminum 330 ml can with a deep green paper label and a subtle mint leaf pattern, and places it on a light wooden desk in the center of the frame, label facing camera. Next to it, a closed laptop edge, a glass of water and a small plant, softly out of focus. Camera: 50 mm lens, f/2.8, slow 10 cm slide to the right. Soft directional light from the left, calm morning mood, neutral grade. No face, no text, no brand logos on the laptop, no extra cans. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Pan right`, intensidad baja.

## 9. Escena 3C — Cocus

**Timecode final:** 00:10,6–00:13.
**Duración Luma:** 5 s. **Recorte:** 2,4 s.

**Fotograma inicial:** vaso con hielo y lima en una mesa de terraza.
**Fotograma final:** rodaja de lima llenando el encuadre.

```text
High-angle product shot on a sunny terrace table. A hand in a neutral sleeve enters from the right holding a matte aluminum 330 ml can with an ocean blue paper label and a subtle ice crystal pattern, and places it next to a tall glass with ice, lime slices and condensation. Camera: 35 mm lens, f/2.8, 30-degree high angle, slow 30-degree orbit to the right, ending with a tilt down toward a lime slice in the glass. Warm sunlight, crisp shadows, fresh summer mood, shallow depth of field. No face, no text, no food, no extra objects. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Orbit right` + `Tilt down`, intensidad
media.

## 10. Escena 4 — La fórmula

**Timecode final:** 00:13–00:18.
**Duración Luma:** 5 s. **Recorte:** 5 s.

**Fotograma inicial:** rodaja de lima cenital llenando el encuadre.
**Fotograma final:** textura del papel de la etiqueta llenando el encuadre.

```text
Top-down macro still life on a cream surface. A line of fresh ingredients from left to right: black tea leaves, green tea leaves, fresh mint, mango cubes, ginger, lime slices, coconut pieces and guarana powder in a small ceramic bowl. At the right end, a matte aluminum 330 ml can lies on its side with a blank cream paper label facing up. Camera: 50 mm lens, f/8, 80 cm above the table, slow slider move left to right, ending with a tilt down and push in toward the paper label. Soft directional light from the left, natural textures, editorial food photography. No text, no sugar cubes, no pills, no supplements, no hands. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Pan right` + `Dolly in`, intensidad baja.

**Nota:** nada de pastillas, cápsulas ni polvos aislados. Solo guaraná en un bol
pequeño, como ingrediente.

## 11. Escena 5 — La receta

**Timecode final:** 00:18–00:21.
**Duración Luma:** 5 s. **Recorte:** 3 s.

**Fotograma inicial:** textura de papel crema.
**Fotograma final:** espiral en el centro de la etiqueta llenando el encuadre.

```text
Extreme macro shot of a matte aluminum 330 ml can lying on a cream surface, with a blank cream paper label facing up. A hand in a neutral sleeve enters from the right and points at the label without covering it. Camera: 100 mm macro lens, f/5.6, 45 degrees above the label, slow pull back and tilt up to reveal the full label, then a slow push in toward a subtle dark green spiral mark in the center of the label. Soft directional light from the left, shallow depth of field, tactile paper texture. No text, no readable letters, no rings, no jewelry, no extra objects. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Dolly out` + `Tilt up`, luego
`Dolly in`, intensidad baja.

**Nota:** la etiqueta sale en blanco. La receta real se compone en postproducción.
La mano solo señala; no debe tapar el texto.

## 12. Escena 6 — Cierre

**Timecode final:** 00:21–00:24.
**Duración Luma:** 5 s. **Recorte:** 3 s.

**Fotograma inicial:** zona crema vacía sobre las latas.
**Fotograma final:** las tres latas alineadas y espacio limpio arriba para el logo.

```text
Frontal product shot of three matte aluminum 330 ml cans on a cream seamless background, evenly spaced left to right: a deep red label with a subtle yellow flame pattern, a deep green label with a subtle mint leaf pattern, and an ocean blue label with a subtle ice crystal pattern. The camera starts on an empty cream area above the cans, then pulls back slowly to reveal the three cans and a clean symmetrical end-card composition. Soft directional light from the left, subtle rim light on the aluminum, calm and tactile. No text, no letters, no logo, no extra objects. 16:9, 5 seconds.
```

**Movimiento de cámara en la interfaz:** `Dolly out`, intensidad baja.

**Nota:** el logo, el eslogan y el aviso legal se añaden en postproducción. No
dejes que Luma invente el logo.

## 13. Transiciones

| De | A | Tipo | Cómo se hace |
| --- | --- | --- | --- |
| S1 | S2 | `Match cut` de color | El `push-in` llena el encuadre con el crema de la etiqueta. S2 abre en crema y revela la espiral verde. Se corta en el fotograma exacto en que el crema ocupa todo. |
| S2 | S3 | `Whip pan` + `color wipe` | Giro de 2 fotogramas hacia Flama y fundido al rojo `#b23a2b`. Se hace en montaje, no en Luma. |
| S3 | S4 | `Match cut` circular | El corte de lima de 3C llena el encuadre. S4 abre cenital con el mismo corte de lima, en el mismo tamaño y posición. |
| S4 | S5 | `Match cut` de textura | La etiqueta de papel llena el encuadre. S5 abre en la misma textura y se aleja. |
| S5 | S6 | `Match cut` de logo | La espiral de la etiqueta se centra. S6 abre con la misma espiral sobre crema, en el mismo tamaño y orientación. |
| S6 | Negro | Corte seco | Corte en la última sílaba. El sonido cae 0,3 s después. |

Si un `match cut` no queda perfecto, el recurso de seguridad es un corte en el
movimiento o un fundido de 4 fotogramas. Nunca una transición de plantilla.

### Transiciones generadas en Luma

Mejor hacerlas en montaje. Si se generan, usar clips de 5 s y recortar:

```text
T1: Macro push-in into a cream paper label until the frame is pure cream, soft directional light, no text, no letters. 16:9, 5 seconds.

T2: Fast whip pan left across a cream set ending on a deep red can label, strong motion blur, red fills the frame, no text. 16:9, 5 seconds.

T3: Top-down macro of a lime slice filling the frame, water droplets, slow push-in, no text. 16:9, 5 seconds.

T4: Macro of cream paper texture filling the frame, soft light, slow drift, no text. 16:9, 5 seconds.

T5: Macro of a subtle dark green spiral mark on cream paper filling the frame, slow push-in, no text. 16:9, 5 seconds.
```

## 14. Continuidad en Luma

- **Misma imagen de referencia:** sube una foto frontal de las tres latas y úsala
  como `reference` o `start frame` en todas las escenas. Sin esa referencia, Luma
  cambia proporciones y colores.
- **Misma semilla:** si la interfaz permite `seed`, repite la misma en todos los
  clips de producto.
- **Mismo formato:** 16:9, máxima resolución disponible, 24 fps.
- **Duraciones:** 5 s para todas las escenas. La escena 3 son tres clips, no uno
  de 7 s.
- **Sin audio:** desactiva el audio de Luma si puedes. La voz en off y la música
  van en postproducción.
- **Sin texto en el prompt:** no pidas el logo de Surge ni la receta escrita.
- **Palabras que no deben entrar en el prompt:** `healthy`, `natural energy`,
  `sustainable`, `Canarian product`. No hacen falta para la imagen y pueden
  colarse en el resultado.
- **Orden de latas:** Flama, Mentisimo y Cocus de izquierda a derecha en todos los
  planos de grupo. Nunca cambia.
- **Etiqueta:** siempre hacia cámara. La costura del papel queda a las 6 en punto.
- **Mano:** la misma mano y el mismo vestuario neutro en S3 y S5. Entra y sale
  siempre por la derecha. Sin logos, sin joyas.
- **Luz:** clave a 45° por la izquierda y contra por la derecha en todas las
  escenas. Cambia el set, no la dirección de la luz.
- **Temperatura:** solo Cocus lleva hielo. Si se muestra una lata caliente, se
  vierte en vaso; nunca se calienta la lata.
- **Logo:** un solo color, sin degradados, sombras ni biseles. No se rota, no se
  redibuja y no se le añaden hojas. Se revela con máscara o luz.
- **Medidas:** 330 ml. No usar el mockup de `assets/brand-presentation.jpg`, que
  mantiene 230 ml y alegaciones pendientes.

## 15. Postproducción obligatoria

- **Etiquetas:** Luma genera etiquetas crema lisas. Componer la etiqueta real con
  logo, nombre, ingredientes, mg de cafeína y aviso.
- **Logo:** usar el SVG o el AI. Animarlo con máscara, sin rotación, sin
  degradados y sin hojas añadidas.
- **Tipografía:** palo seco limpia con toques orgánicos. No generarla con IA.
- **Voz en off:** añadir en edición con los timecodes de la sección 16.
- **Aviso de cafeína:** va en la descripción del vídeo. Si legal exige que
  aparezca en pantalla, ampliar el cierre o recortar otra escena.
- **Cierre:** sin web ni redes si el equipo no las aporta. No constan en las
  fuentes.
- **Color:** grado neutral. No alterar los hexadecimales de las latas:
  Flama `#b23a2b`, Mentisimo `#2d6a4f`, Cocus `#1f4e5f`.

## 16. Voz en off con timecode

| Timecode | Texto |
| --- | --- |
| 00:00.0 | «Esto no es un golpe de energía.» |
| 00:03.2 | «Es energía que surge.» |
| 00:05.2 | «Tres latas. Tres momentos.» |
| 00:06.4 | «Flama para el push.» |
| 00:08.4 | «Mentisimo para el día a día.» |
| 00:10.7 | «Cocus para el frescor.» |
| 00:13.2 | «Cafeína de té y guaraná, sin cafeína aislada.» |
| 00:16.2 | «Sin azúcar añadido.» |
| 00:18.2 | «La receta, publicada en cada lata.» |
| 00:21.2 | «Surge. Energía + natural − agresiva.» |

## 17. Lo que no se puede decir ni mostrar

- Precios. El PVP de 1,95 € es `[SUPUESTO]` hasta tener cotizaciones y escandallo.
- «Producto canario», «hecho en Canarias», «km 0» o «coco local».
- «Sostenible», «eco», «verde», «cero residuo», «cero huella», «no contamina» o
  «sin plástico» sin datos y certificados.
- «Saludable», «100 % natural», «sin rebote», «sin pico», «energía sostenida»,
  «concentración balanceada» o «sin efectos adversos».
- «El mismo golpe que Red Bull».
- Web, teléfono o redes sociales que no estén aportados por el equipo.
- Menores, embarazadas o personas sensibles como destinatarios. El aviso de
  cafeína es obligatorio en la etiqueta: «Contenido elevado de cafeína. No
  recomendado para niños ni para mujeres embarazadas o en período de lactancia.»

## 18. Fuentes

- `branding.md` — nombre, eslogan, valores, tono, paleta y origen canario.
- `origin.md` — historia del equipo y motivo de la marca.
- `goal.md` — objetivo de entrada en el mercado español.
- `analisis-interno/propuesta-de-valor.md` — qué se dice y qué no se dice.
- `analisis-interno/4ps/producto.md` — recetas, cafeína, azúcares, envase y
  momentos.
- `analisis-interno/4ps/precio.md` — precio objetivo y cifras `[SUPUESTO]`.
- `analisis-interno/4ps/promocion.md` — campaña de los tres momentos y canales.
- `analisis-interno/4ps/punto-de-venta.md` — canales de venta.
- `historia-del-logotipo.md` — lectura y reglas de uso del logo.
- `config/communication.md` — tono, patrones y formato.
- `diapositivas.md` — avisos legales y huecos del proyecto.

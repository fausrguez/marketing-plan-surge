# 36 — Objetivos SMART

- **Diapositiva:** 36 de 54
- **Índice:** [diapositivas.md](../diapositivas.md)

- **Sección:** Objetivos · **Tipo:** título + frase + infografía SMART
- **Texto actual:** «OBJETIVOS» · «Plantearemos objetivos SMART y realistas para
  nuestro proyecto» + cinco cheurones (específico, medible, alcanzable,
  relevante, temporal).
- **Estado:** objetivos escritos y M0 fijado: 26 de junio de 2027, lanzamiento en
  Bestial Race.
- **Fuente en el repo:** `metrics.md`, `goal.md`,
  `analisis-interno/4ps/punto-de-venta.md`, `analisis-interno/4ps/precio.md`,
  `target.md`.
- **Criterio de cierre:** cada objetivo se mide con una métrica que ya está en
  `metrics.md`, ninguno necesita un panel nuevo, y M0 está sustituido por una
  fecha.
- **Aviso:** sin histórico, todas las cifras son `[SUPUESTO]`. Se declara el
  método de cálculo, no sólo el número. No se publican objetivos de facturación
  hasta que `precio.md` cierre el PVP.

## 1. Frase de la diapositiva

«Cuatro objetivos, una isla y doce meses. Cada uno se mide con una cifra que ya
tenemos; ninguno necesita un panel nuevo.»

M0 = día en que hay stock vendible de las tres latas: **26 de junio de 2027**,
lanzamiento en Bestial Race.

## 2. Los cuatro objetivos

| # | Objetivo | Cifra | Plazo | Responsable | Métrica de `metrics.md` |
| --- | --- | ---: | --- | --- | --- |
| O1 | Puntos de venta activos en Gran Canaria | 8 puntos | M0+3 meses | Antonio | Puntos de venta conseguidos |
| | | 15 puntos | M0+12 meses | | |
| O2 | Rotación media por punto de venta | 12 latas/punto/semana | M0+3 | Antonio | Latas vendidas por tienda y semana, por SKU |
| | | 24 latas/punto/semana | M0+6 | | |
| O3 | Suscriptores activos de la tienda online | 40 suscriptores | M0+3 | `[SUPUESTO: Antonio]` | Suscriptores de la tienda online · Bajas de suscripción |
| | | 100 suscriptores | M0+12 | | |
| O4 | Personas alcanzadas con muestras | 2.000 personas | M0+6 | Carla | Personas alcanzadas con muestras · % de muestras con edad verificada |

Cifras `[SUPUESTO]`: no hay histórico de ventas ni de captación.

## 3. Lectura SMART, chevrón a chevrón

### O1 · Puntos de venta

- **Específico:** puntos con pedido y sell-out reales en Gran Canaria, no visitas
  ni contactos.
- **Medible:** cuenta como activo el punto con al menos 1 caja de 24 latas al mes
  y 4 semanas seguidas de venta registrada.
- **Alcanzable:** hay 14 prospectos ya identificados en `punto-de-venta.md`
  (6 gimnasios y estudios, 6 cafeterías y tiendas, 1–2 Decathlon). 8 de 14 es un
  57 % de cierre; el alta cuesta 0–300 € `[SUPUESTO]`.
- **Relevante:** es la métrica que desbloquea la distribución y la que exige
  `goal.md` («desarrollar canales de venta»). Sin lineal no hay prueba.
- **Temporal:** 8 a M0+3, 15 a M0+12. El test de Decathlon son 8 semanas antes de
  ampliar (`punto-de-venta.md`).

### O2 · Rotación

- **Específico:** latas vendidas al consumidor final por punto y semana, separadas
  por SKU.
- **Medible:** sell-out, no sell-in. Se pide el dato al punto cada lunes o se
  estima por reposición.
- **Alcanzable:** 12 latas/semana son menos de dos al día por punto; 24 son tres o
  cuatro, el ritmo de una nevera de gimnasio o de una cafetería con público activo.
  Con los puntos activos a M0+6 (unos 12, entre los 8 de M0+3 y los 15 de M0+12),
  24 latas/punto/semana ≈ 1.240 latas/mes, dentro de las 1.800 latas/mes que el
  piloto asigna al canal físico. El suelo de salida ya está fijado en 24 latas al
  mes por punto.
- **Relevante:** convierte «estamos en la tienda» en «se vende». Es la única
  forma de saber si el precio de 1,95 € funciona en el lineal.
- **Temporal:** 12 a M0+3; 24 a M0+6. Reparto por SKU `[SUPUESTO]`: Flama 50 %,
  Mentisimo 35 %, Cocus 15 %.

### O3 · Suscriptores

- **Específico:** suscripciones de pago activas en la tienda online, en el modelo
  de 24 latas de `precio.md`.
- **Medible:** «activo» = compra en los últimos 60 días. Bajas y churn se leen en
  la misma pantalla.
- **Alcanzable:** 40 suscriptores son 960 latas/mes, que con la compra única
  encajan en las 1.200 latas/mes online del piloto. La suscripción ya está
  construida y presupuestada (3.000 €).
- **Relevante:** es el canal con mejor margen y el que mide recompra. Es el
  indicador que `goal.md` llama «captar los primeros clientes».
- **Temporal:** 40 a M0+3; 100 a M0+12. Churn objetivo ≤ 5 %/mes `[SUPUESTO]`.
  Aviso: 100 suscriptores son unas 2.400 latas/mes y ya no caben en el modelo de
  3.000; exigen segunda producción.

### O4 · Muestras

- **Específico:** personas adultas que prueban una lata en gimnasios, boxes,
  carreras, coworkings y eventos.
- **Medible:** 3.000 latas de muestra ya presupuestadas ÷ 1,5 latas por persona
  ≈ 2.000 personas. Canje del QR del 15 % → 300 primeras compras.
- **Alcanzable:** las 3.000 latas están dentro de la partida de producción y los
  4.000 € en activaciones. El QR ya está previsto en `promocion.md` §2.
- **Relevante:** es la métrica de prueba del producto y la que alimenta la
  encuesta de `target.md` §8. Sin edad verificada, la muestra es un riesgo legal.
- **Temporal:** 2.000 personas a M0+6, repartidas por las tres latas. Exigencia
  de ≥ 95 % de muestras con edad verificada en todo momento.

## 4. Objetivo de control: recompra del pack

No va en los cuatro cheurones, pero se mide igual. Sin él no se sabe si el pack
de variedades funciona como prueba o sólo canibaliza (`metrics.md`).

| Objetivo | Cifra | Plazo | Responsable | Métrica |
| --- | ---: | --- | --- | --- |
| Recompra tras el pack de variedades | 250 packs vendidos y 25 % repite la misma lata | M0+6, ventana de 60 días | Antonio | Ventas del pack de variedades · Recompra por SKU |

250 packs es el mínimo para que el 25 % distinga de un 15 % con margen
suficiente. El pack de 6 latas a 11,50 € ya existe como unidad de prueba
(`precio.md` §3).

## 5. Lo que no entra y por qué

| Descartado | Motivo |
| --- | --- |
| Objetivo de facturación (7.500 €/mes del Miro) | `precio.md` mantiene tres precios en conflicto y el IGIC sin confirmar. Cifra sobre precio abierto = cifra inventada |
| Objetivo de seguidores en RRSS | `metrics.md` dice que se calibran con el primer mes. Un número ahora contradice el archivo |
| Objetivo de sostenibilidad | Sin LCA ni datos de proveedor no hay cifra que publicar |
| Objetivo de 12 meses en península | La fase 1 es Gran Canaria; el distribuidor no está firmado |

## 6. Pendiente para cerrar

1. **M0:** fecha de primera producción. Responsable: Antonio. Sin ella, O1–O4 no
   se convierten en calendario.
2. **Responsables de O3 y O4:** propuestos por proximidad, no asignados en ningún
   archivo. Confirmar en la próxima reunión.
3. **Canje del QR:** el 15 % es `[SUPUESTO]`. Se recalibra con la primera
   activación; si sale al 8 %, se reescala O4, no se maquilla la cifra.
4. **Reparto por SKU de O2:** validar con el primer mes de sell-out real.

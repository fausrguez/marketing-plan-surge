# Propuesta de precio

**Estado:** estimación para decidir, no escandallo final.
**Fecha:** 21 de octubre de 2026.
**Base:** tres latas de 330 ml, sin gas, 10.000 unidades por SKU y 30.000 en el
lanzamiento `[SUPUESTO: confirmar MOQ]`.

> Este archivo propone una arquitectura de precio y de canales. No sustituye a
> `precio.md`: lo aterriza con las recetas de `producto.md`. Todas las cifras son
> `[SUPUESTO]` hasta tener tres cotizaciones de copacker, coste real de envío y
> confirmación fiscal.

## TLDR

- **Flama y Mentisimo: 1,95 €/lata.** Es el precio de «premium de acceso» que
  mantiene la marca por debajo de 2 € y por encima de la energética convencional.
- **Cocus: 1,95 € solo con coco concentrado; 2,20 € si se usa agua de coco
  fresca.** Con coco fresco a 2,20 €/L, el COGS se acerca a 0,90 € y el margen
  de distributor desaparece.
- **Packs:** 4 Flama 7,50 € + envío; variedades 6 latas 11,50 € + envío;
  suscripción 12 latas 22,90 € con envío incluido. No regalar envío en packs de
  4 o 6: se come el margen.
- **Distribución:** prioridad a venta directa online y a tiendas/gimnasios sin
  distributor. El distributor solo entra con volumen y a 0,95–1,00 €/lata.
- **Objetivo de COGS:** ≤ 0,70 €/lata para que 1,95 € funcione en retail. Si el
  COGS pasa de 0,80 €, hay que subir precio, reformular o vender más directo.

## 1. Supuestos de coste

| Concepto | Supuesto | Nota |
| --- | --- | --- |
| Producción | 10.000 latas por SKU; 30.000 total | `[SUPUESTO: MOQ]` |
| Formato | Lata 330 ml, aluminio, etiqueta de papel FSC | `producto.md` |
| Impuesto | 10 % IVA/IGIC incluido en PVP | `[PENDIENTE: asesor fiscal]` |
| Canal | Venta directa a tienda, sin distributor, salvo que se indique | Base conservadora |
| Ingredientes | Compra mayorista, temporada y volumen de 10.000 latas | `[SUPUESTO]` |
| Coco | Dos escenarios: concentrado y agua de coco fresca | Decisión pendiente |
| Merma | 3–5 % de producción y calidad | `[SUPUESTO]` |
| Coste de marketing | Fuera del COGS; es inversión de lanzamiento | No se carga a la lata |

## 2. Coste estimado por lata

### 2.1 Ingredientes

Precios unitarios de referencia `[SUPUESTO: cotizar con proveedor]`:

| Ingrediente | Precio | Flama | Mentisimo | Cocus |
| --- | ---: | ---: | ---: | ---: |
| Té negro | 30 €/kg | 0,096 € (3,2 g) | — | — |
| Té verde | 35 €/kg | — | 0,123 € (3,5 g) | — |
| Puré de mango | 3,00 €/kg | 0,105 € (35 g) | — | — |
| Menta fresca | 9 €/kg | — | 0,135 € (15 g) | — |
| Zumo de lima | 9 €/kg | 0,045 € (5 g) | 0,045 € (5 g) | 0,090 € (10 g) |
| Piel de lima | 12 €/kg | — | 0,024 € (2 g) | — |
| Jengibre fresco | 4 €/kg | 0,032 € (8 g) | — | 0,024 € (6 g) |
| Guaraná en polvo | 30 €/kg | 0,033 € (1,1 g) | 0,027 € (0,9 g) | 0,060 € (2,0 g) |
| Pimienta negra | 20 €/kg | 0,003 € (0,15 g) | — | — |
| Agua de coco | 2,20 €/L | — | — | 0,396 € (180 ml) |
| Agua y proceso | 0,01 €/lata | 0,010 € | 0,010 € | 0,010 € |
| **Total ingredientes** | | **0,324 €** | **0,364 €** | **0,580 €** |

Con coco concentrado a 1,20 €/L equivalente, el agua de coco baja a 0,216 € y el
total de ingredientes de Cocus queda en **0,400 €**. La etiqueta debe declarar
«agua de coco concentrada» o el nombre que corresponda.

### 2.2 Envase, fabricación y logística

| Concepto | Base | Rango | Nota |
| --- | ---: | ---: | --- |
| Lata + tapa 330 ml | 0,090 € | 0,080–0,130 € | Aluminio |
| Recargo contenido reciclado | 0,010 € | 0,010–0,030 € | Solo con certificado |
| Etiqueta FSC + aplicación | 0,030 € | 0,020–0,040 € | Una por SKU |
| Secundario de cartón | 0,020 € | 0,010–0,030 € | Sin retráctil |
| **Envase total** | **0,150 €** | **0,120–0,230 €** | |
| Copacking y pasteurización | 0,100 € | 0,080–0,180 € | `[SUPUESTO: 30.000 latas]` |
| Logística inbound/outbound | 0,050 € | 0,040–0,090 € | Canarias vs península |
| Merma y control de calidad | 0,020 € | 0,010–0,040 € | 3–5 % |
| **Total no ingrediente** | **0,320 €** | **0,250–0,540 €** | |

### 2.3 COGS estimado

| SKU | Ingredientes | Envase + fabricación + logística | COGS base | Rango prudente |
| --- | ---: | ---: | ---: | ---: |
| Flama | 0,324 € | 0,320 € | **0,644 €** | 0,55–0,80 € |
| Mentisimo | 0,364 € | 0,320 € | **0,684 €** | 0,58–0,85 € |
| Cocus con concentrado | 0,400 € | 0,320 € | **0,720 €** | 0,62–0,88 € |
| Cocus con coco fresco | 0,580 € | 0,320 € | **0,900 €** | 0,78–1,05 € |

**Lectura:** Flama y Mentisimo caben en el objetivo de 0,60–0,70 €. Cocus con coco
fresco no cabe: o se usa concentrado, o se sube el precio, o se vende
principalmente directo.

## 3. Cascada de precio a 1,95 €

Para un PVP de 1,95 € con 10 % de impuesto incluido `[SUPUESTO]`:

| Paso | €/lata | Nota |
| --- | ---: | --- |
| PVP | 1,950 | Impuesto incluido |
| Impuesto (10 %) | 0,177 | IGIC/IVA a confirmar |
| Precio neto | 1,773 | Sin impuesto |
| Margen tienda (35 %) | 0,620 | `[SUPUESTO]` |
| **Wholesale a tienda** | **1,153** | Lo que cobra Surge |
| Margen distributor (18 %) | 0,207 | Solo si hay distributor |
| **Neto para Surge con distributor** | **0,946** | Antes de COGS |
| COGS Flama | 0,644 | |
| Contribución Flama con distributor | 0,302 | 32 % sobre neto |
| COGS Mentisimo | 0,684 | |
| Contribución Mentisimo con distributor | 0,262 | 28 % sobre neto |
| COGS Cocus concentrado | 0,720 | |
| Contribución Cocus con distributor | 0,226 | 24 % sobre neto |
| COGS Cocus fresco | 0,900 | |
| Contribución Cocus fresco con distributor | 0,046 | 5 % sobre neto |

Si Surge vende directo a la tienda, sin distributor, se queda el margen del
distributor: la contribución sube a **0,51 € en Flama**, **0,47 € en Mentisimo** y
**0,43 € en Cocus concentrado**. Con Cocus fresco baja a **0,25 €**.

### Sensibilidad del margen directo a tienda

| COGS | Contribución a 1,15 € wholesale | Margen sobre wholesale |
| ---: | ---: | ---: |
| 0,60 € | 0,55 € | 48 % |
| 0,65 € | 0,50 € | 43 % |
| 0,70 € | 0,45 € | 39 % |
| 0,75 € | 0,40 € | 35 % |
| 0,80 € | 0,35 € | 30 % |
| 0,90 € | 0,25 € | 22 % |

## 4. Precio recomendado por formato

| Formato | PVP | €/lata | Envío | Uso |
| --- | ---: | ---: | --- | --- |
| Lata individual | 1,95 € | 1,95 € | — | Impulso y prueba |
| Pack 4 Flama | 7,50 € | 1,88 € | 3,95 € | Prueba del héroe |
| Pack variedades 6 | 11,50 € | 1,92 € | 3,95 € | Probar los tres moods |
| Suscripción 12 | 22,90 € | 1,91 € | Incluido | Recompra y margen |
| Cocus individual con coco fresco | 2,20 € | 2,20 € | — | Solo si no se usa concentrado |

El pack de 6 no es un pack de ahorro: sale a 1,92 €/lata, más caro por lata que el
pack de 4. Es una unidad de prueba y de regalo, no un descuento. No comunicarlo
como «ahorra» ni como «más barato por lata».

## 5. Precio por canal

| Canal | PVP recomendado | Wholesale | Margen del canal | Cuándo usarlo |
| --- | ---: | ---: | ---: | --- |
| Web directa | 1,95 € | — | — | Siempre |
| Suscripción | 22,90 €/12 | — | — | Siempre |
| Tienda especializada | 1,95 € | 1,15 € | 35 % | Lanzamiento |
| Gym / cafetería | 2,20–2,50 € | 1,35–1,50 € | 30–40 % | Lanzamiento |
| Horeca | 2,50–2,80 € | 1,50–1,65 € | 35–40 % | Selectivo |
| Distributor | 1,95 € | 0,95–1,00 € | 15–20 % | Solo volumen |
| Marketplace | 1,95 € | — | 15 % comisión | Test |

### Precio por caja de 24 latas

| Canal | €/lata | Caja de 24 |
| --- | ---: | ---: |
| Tienda directa | 1,15 € | 27,60 € |
| Gym / cafetería | 1,35–1,50 € | 32,40–36,00 € |
| Horeca | 1,50–1,65 € | 36,00–39,60 € |
| Distributor | 0,95–1,00 € | 22,80–24,00 € |

Pedido mínimo recomendado: **24 latas o 6 packs**. Primera compra a tienda nueva:
pago anticipado o contra reembolso; a partir de la segunda, 30 días.

## 6. Packs y envío

### Pack 4 Flama — 7,50 € + envío

- Neto sin impuesto: 6,82 €.
- COGS de 4 latas: 2,58 €.
- Contribución antes de envío y fulfillment: 4,24 €.
- Si Surge regala el envío (4,50–6,00 €), la contribución cae a −0,26 / −1,76 €.
- **Decisión:** cobrar 3,95 € de envío o incluir el pack en el umbral de envío
  gratis de 30 €.

### Pack variedades 6 — 11,50 € + envío

- Neto sin impuesto: 10,45 €.
- COGS medio de 6 latas: 4,10 €.
- Contribución antes de envío y fulfillment: 6,35 €.
- Si se regala el envío, quedan 0,35–1,85 € antes de fulfillment; con fulfillment,
  el pack puede quedarse en cero.
- **Decisión:** cobrar envío. El pack de 6 sirve para probar, no para subsidiar.

### Suscripción 12 — 22,90 € con envío incluido

- Neto sin impuesto: 20,82 €.
- COGS medio de 12 latas: 8,20 €.
- Envío: 4,50–6,00 €.
- Fulfillment: 0,25–0,35 €/lata = 3,00–4,20 €.
- Contribución: **2,42–5,12 € por caja**, es decir, **0,20–0,43 €/lata**.
- Con Cocus fresco, la contribución puede bajar a 0,05–0,15 €/lata.
- **Decisión:** la suscripción es el canal que mejor protege el margen, pero solo
  si el mix no es 100 % Cocus fresco.

### Política de envío recomendada

- Envío estándar: 3,95 €.
- Envío gratis a partir de 30 €.
- Suscripción: envío incluido.
- No envío gratis en pack de 4 ni de 6 por separado.
- Canarias: recargo real de transporte; no esconderlo en el PVP.

## 7. Distribución recomendada

### Fase 1 — Canarias

1. **Venta directa online** con suscripción y packs. Es el canal con mejor margen y
   el que da datos de recompra.
2. **Gimnasios, cafeterías y tiendas de productos naturales** de Gran Canaria.
   Venta directa, sin distributor, a 1,15–1,50 €/lata según canal.
3. **Eventos y carreras** como muestreo y prueba, no como canal principal.
4. **Sin distributor generalista** al principio: el volumen no compensa el 18–20 %
   de margen que se lleva.

### Fase 2 — Península

- Entrar con distributor solo para cuentas que no se pueden atender directo.
- Precio mínimo al distributor: 0,95 €/lata. Por debajo, no entra.
- El distributor debe dar servicio, no solo almacenar: pedidos mínimos, reposición
  y información de sell-out.
- Mantener cuentas clave (gimnasios grandes, cadenas de café, coworkings) en
  directo aunque haya distributor.

### Horeca y gimnasios

- PVP 2,20–2,50 € en gimnasio/cafetería; 2,50–2,80 € en horeca.
- Wholesale 1,35–1,65 €/lata.
- Formato de entrada: caja de 24 latas.
- No dar nevera gratis al principio; negociar expositor solo con pedido mínimo.

## 8. Comparación con la competencia

| Referencia | Formato | PVP orientativo | Posición |
| --- | --- | ---: | --- |
| Energética convencional | 250 ml | 1,20–1,80 € | Volumen y azúcar |
| Celsius | 355 ml | 2,50–3,20 € | Fitness, importada |
| AG1 / Spacegoods | Polvo | 1,50–3,00 €/ración | Wellness, no RTD |
| Surge | 330 ml | 1,95 € | Natural, tres moods, premium de acceso |

`[SUPUESTO: precios de mercado sin estudio actualizado]`. La ventaja de Surge no es
ser más barata: es dar una lata lista para tomar, con receta publicada y tres
momentos, a menos de 2 €.

## 9. Recomendación final

1. **Mantener 1,95 €** para Flama y Mentisimo. Es el precio que sostiene el
   posicionamiento de masas y sigue siendo premium frente a la energética
   convencional.
2. **Cocus:** usar concentrado y mantener 1,95 €, o usar coco fresco y subir a
   2,20 €. No lanzar Cocus fresco a 1,95 € con distributor: la contribución es
   casi cero.
3. **Packs:** 4 Flama 7,50 € + envío; variedades 11,50 € + envío; suscripción
   22,90 € con envío incluido. No hacer descuentos de lanzamiento.
4. **Canal:** directo a tienda y online primero. Distributor solo con volumen y a
   partir de 0,95 €/lata.
5. **COGS:** cerrar tres cotizaciones. Si el COGS medio supera 0,75 €, revisar
   precio de Cocus, tamaño de tirada o receta antes de imprimir.
6. **Impuesto:** confirmar IGIC/IVA. Con IGIC 7 % el margen mejora unos 0,03 €/lata;
   con un tipo superior al 10 %, el modelo de 1,95 € se estrecha.

## 10. Pendiente para convertir esta propuesta en precio real

- Tres cotizaciones de copacker a 10.000 y 15.000 por SKU.
- Coste real de mango, menta, lima, jengibre, coco, té y guaraná con las cantidades
  de `producto.md`.
- Decisión coco fresco vs concentrado y su impacto en etiqueta.
- Coste real de envío de 4, 6 y 12 latas a Canarias y península.
- Margen real de tienda, gimnasio, horeca y distributor.
- Tipo de IGIC/IVA aplicable.
- MOQ y plazo de producción.
- Test de elasticidad: 1,95 € vs 2,20 € vs 2,50 € en tienda y online.
- Tasa de recompra y churn de la suscripción.

## 11. Criterio de cierre

Esta propuesta se cierra cuando:

1. El COGS de las tres latas sale de cotizaciones reales, no de este archivo.
2. El PVP de 1,95 € deja una contribución ≥ 0,35 €/lata en venta directa a tienda.
3. Cocus tiene una decisión cerrada: concentrado a 1,95 € o fresco a 2,20 €.
4. La suscripción de 22,90 €/12 cubre envío, fulfillment y COGS con margen.
5. El distributor no baja de 0,95 €/lata.
6. IGIC/IVA y margen de canal están confirmados por escrito.

# SLEEP'N · Propuesta para Paseo de las Delicias, 16 — página exclusiva del proyecto

Copia de la landing de expansión (repositorio gorka-debug/sleepn_expansion, el mismo `index.html` que el paquete
`sleepn-activos-produccion`) adaptada a la propiedad de Delicias 16. Mismo diseño y mismo HTML + CSS sin JavaScript.

## Orden de la página

1. Portada: antetítulo «Propuesta para Paseo de las Delicias, 16 · Madrid» y botón «Ver la propuesta» (abre la carta de intenciones en PDF).
2. Qué hacemos.
3. Nuestros hoteles.
4. Nuestra oferta: condiciones de la carta de intenciones del 24/11/2026, renta mínima garantizada por año y enlace a la propuesta completa.
5. Proyección de la renta: resumen de «Proyeccion_20_Anos_Hotel_Delicias_16.xlsx» con 3 cifras clave, un gráfico de los 20 años
   (azul: se paga la renta mínima; coral: se paga la variable del 32 %) y una tabla de años clave (1 a 6, 8, 10, 15, 20 y total).
6. Inspiración · Así quedaría tu edificio: fachada (SLEEP'N Atocha); recepción y zonas comunes (SLEEP'N Valencia y SLEEP'N Atocha);
   habitaciones, baños y desayunos (SLEEP'N Valencia); y 8 detalles: SHOPP'N, LOCK'N, señalética, puertas, pasillos, WALK'N,
   packaging y el barrio. Cada grupo de fotos lleva debajo el hotel del que es.
7. Reconocimientos.
8. Equipo gestor.

Fuera: Resultados comprobados, Dos formas de unirte (Desarrollo, gestión y criterios) y Hablemos de tu inmueble.
El email y el teléfono de Gonzalo pasan al pie. La página lleva `noindex, nofollow` y no tiene `canonical`.

## Ficheros nuevos

- `docs/propuesta-arrendamiento-delicias16.pdf`: la carta de intenciones con el formato de la web (Jost y DM Sans, colores y logo
  de SLEEP'N). Sale de «Propuesta_Arrendamiento_Hotel_Delicias_16_SLEEPN.docx»; si se cambia el Word, se vuelve a exportar a PDF
  con este mismo nombre. Es la carta del 24/11/2026. Respecto al Word recibido: «Renta Variable*» y «ventas netas*» llevan
  un asterisco con la nota «Ventas netas: ventas sin IVA una vez descontadas las comisiones de las agencias de viaje online
  (OTAs)»; se añade al final un anexo con la proyección (la misma de la web); y se corrigen «lavababos» → «lavabos» y
  «B- Corp» → «B Corp». La introducción se deja como está, aunque aún habla de «diferimiento inicial».
- `img/inspiracion/`: 27 fotos del zip `Archivo` (Fachada, RECEPCION, Habitación, Baño, DYN, Detalles, Pasillos, Puertas,
  Generales, SHOPP'N, LOCK'N y Señalítica). Las nuevas están recortadas a 3:2 o 4:5 y a 1.200 px de ancho como máximo;
  a las tres de recepción de SLEEP'N Atocha y a la de la estación de Atocha se les ha quitado la franja de sellos de abajo.

## Fotos del zip que no se usan

- `Pasillos/hallways--v16003554.jpg`: lleva la marca de agua de Tripadvisor.
- Recepción: `caption 2`, `caption3`, `image` y `nuestra-recepcion`. Desayunos: `746`, `775`, `900` y `caption 5`. SHOPP'N: `937`.
  Están bien; se han dejado fuera para que cada bloque tenga 3 fotos. Se pueden cambiar por otras sin tocar el diseño.

## Oferta: de dónde sale cada dato (carta de intenciones)

| En la página | Apartado de la carta |
|---|---|
| 20 años, 5 de obligado cumplimiento | 3 |
| Renta: la mayor entre el 32 % de las ventas netas* y la RMG | 4 y nota * |
| RMG 756.000 €/año (18.000 €/hab.), IPC desde el año 4 con tope del 2,5 % | 4 |
| Carencia de 6 meses (proyecto de interiorismo, obras de la planta baja, amueblamiento y apertura) | 4 |
| RMG por año: 378 k€ el año 1 (6 meses de carencia) · 756 k€ los años 2 y 3 · 756 k€ + IPC desde el año 4 | 4 (el año 1, del Excel) |
| Inversión de 840.000 € (20.000 €/hab.); las instalaciones fijas de la planta baja quedan en el inmueble | 2 |
| Aval de una anualidad de RMG (máx. 756.000 €), 6 mensualidades (378.000 €) desde el año 7 si se han cumplido los pagos | 5 |
| Rentas netas de IVA; IBI, tasas de basuras y residuos y seguro del continente, de la propiedad | 4 |

## Proyección: de dónde sale cada dato (Excel)

Todo sale de «Proyeccion_20_Anos_Hotel_Delicias_16.xlsx», hoja «Proyección 20 Años Delicias 16». Las cifras se han recalculado
fuera del Excel y coinciden al céntimo.

- Ventas netas = ventas sin IVA (columna B) menos las comisiones de OTAs al 7,5 % (columna D).
- Renta variable = 32 % de las ventas netas (columna E); renta mínima con IPC al 2,5 % desde el año 4 (columna F); renta a pagar,
  la mayor de las dos (columna G).
- Año 6: primer año en variable (817.138 € frente a 814.129 € de mínima). Del 6 al 20, 15 años en variable.
- Renta total en 20 años: 18.881.805 € (18,9 M€). Año 20: 1.270.021 €.
- Si cambia el Excel, hay que regenerar el gráfico, la tabla y el anexo de la carta.

## Dónde subirlo

En una carpeta propia, por ejemplo `https://sleepn.eco/delicias16/`, con `index.html`, `img/` y `docs/` tal cual.

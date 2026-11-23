# SLEEP'N · Propuesta para Paseo de las Delicias, 16 — página exclusiva del proyecto

Copia de la landing de expansión (repositorio gorka-debug/sleepn_expansion, el mismo `index.html` que el paquete
`sleepn-activos-produccion`) adaptada a la propiedad de Delicias 16. Mismo diseño y mismo HTML + CSS sin JavaScript.

## Orden de la página

1. Portada: antetítulo «Propuesta para Paseo de las Delicias, 16 · Madrid» y botón «Ver la propuesta» (abre la carta de intenciones en PDF).
2. Qué hacemos.
3. Nuestros hoteles.
4. Nuestra oferta: condiciones de la carta de intenciones del 23/11/2026, renta mínima garantizada por año y enlace a la propuesta completa.
5. Inspiración · Así quedaría tu edificio: fachada (SLEEP'N Atocha); recepción y zonas comunes (SLEEP'N Valencia y SLEEP'N Atocha);
   habitaciones, baños y desayunos (SLEEP'N Valencia); y 8 detalles: SHOPP'N, LOCK'N, señalética, puertas, pasillos, WALK'N,
   packaging y el barrio. Cada grupo de fotos lleva debajo el hotel del que es.
6. Reconocimientos.
7. Equipo gestor.

Fuera: Resultados comprobados, Dos formas de unirte (Desarrollo, gestión y criterios) y Hablemos de tu inmueble.
El email y el teléfono de Gonzalo pasan al pie. La página lleva `noindex, nofollow` y no tiene `canonical`.

## Ficheros nuevos

- `docs/propuesta-arrendamiento-delicias16.pdf`: la carta de intenciones con el formato de la web (Jost y DM Sans, colores y logo
  de SLEEP'N). Sale de «Propuesta_Arrendamiento_Hotel_Delicias_16_SLEEPN.docx»; si se cambia el Word, se vuelve a exportar a PDF
  con este mismo nombre. Respecto al Word original solo cambian la renta variable del apartado 4 (35 %, igual que en la
  introducción; el original decía 32 %) y la errata «lavabaos» → «lavabos».
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
| 20 años, 5 de obligado cumplimiento, salidas cada 5 años con 12 meses de preaviso | 3 |
| Renta: la mayor entre el 35 % de las ventas netas y la RMG | 4 |
| RMG base 756.000 €/año (18.000 €/hab.), IPC desde el año 4 con tope del 2,5 % | 4 |
| Carencia de 4 meses | 4 |
| RMG por año: 504 · 609 · 693 · 910 (años 4 a 6) · 756 k€ + IPC desde el año 7 | 4, tabla |
| 462.000 € diferidos que se recuperan en los años 4 a 6 (154.000 €/año) | 4 |
| Inversión de 840.000 € (20.000 €/hab.); las instalaciones fijas de la planta baja quedan en el inmueble | 2 |
| Aval de una anualidad de RMG (máx. 756.000 €), 6 mensualidades (378.000 €) desde el año 7 | 5 |
| Rentas netas de IVA; IBI y seguro del continente, de la propiedad | 4 |

## Dónde subirlo

En una carpeta propia, por ejemplo `https://sleepn.eco/delicias16/`, con `index.html`, `img/` y `docs/` tal cual.

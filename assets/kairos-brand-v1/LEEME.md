# Kairos — Assets de marca V1

Reconstrucción vectorial manual de la lámina aprobada proporcionada por el usuario. Conserva el doble arco abierto, eje vertical afilado, curvas interiores, punto y estrellas de orientación, y composición vertical con KAIROS. Al partir de un PNG, los contornos son una reconstrucción de la referencia, no la recuperación de un original vectorial. Las letras se reconstruyeron como trazados geométricos limpios manteniendo su aspecto y espaciado; no se presupone una tipografía exacta.

## Archivos

| Archivo | viewBox / dimensiones | Uso |
|---|---|---|
| kairos-symbol.svg | 0 0 320 340 | Isotipo dorado transparente, preferentemente sobre vino o grafito. Recomendado desde 48 px de alto. |
| kairos-logo.svg | 0 0 500 430 | Composición vertical, isotipo y wordmark vino, transparente, para fondos claros. Recomendado desde 200 px de ancho. |
| kairos-logo-light.svg | 0 0 500 430 | Composición vertical transparente: isotipo dorado y wordmark arena, para vino o grafito. |
| kairos-favicon.svg | 0 0 360 360 | Variante óptica para 16–48 px, con fondo vino y esquinas redondeadas. |
| kairos-avatar-1024.png | 1024 × 1024 px | Fondo vino sólido y símbolo dorado centrado. |
| kairos-avatar-512.png | 512 × 512 px | La misma composición a 512 px. |

## Colores y adaptaciones

- Vino tinto: #4A0E1A.
- Dorado suave: #D4AF7C.
- Arena: #EADCC8.
- Grafito: #1F1F1F, fondo de uso recomendado; no se necesita en estos seis archivos.
- No se modificaron los hexadecimales solicitados. Los efectos de iluminación, textura y variaciones tonales del PNG se sustituyeron por color plano para producción.
- En la versión clara se usa vino para ambos elementos, siguiendo la variante clara de la referencia.
- El favicon refuerza arcos y punto de referencia y simplifica curvas. Mantiene la misma estructura; usa fondo vino para asegurar consistencia visual.
- Se omiten descriptor y lema porque los entregables solicitados incluyen únicamente isotipo y KAIROS.

## Verificación

Los cuatro SVG contienen geometría vectorial con viewBox, sin imágenes incrustadas, texto dependiente de fuentes, scripts, referencias externas ni dependencias web. Los avatares se renderizaron desde la misma geometría vectorial.

Se renderizaron e inspeccionaron favicon e isotipo a 16, 32 y 48 px. A 16 px el favicon conserva la silueta general, pero sus detalles interiores convergen por la resolución disponible. A 32 y 48 px se distinguen mejor los arcos y referencias. El isotipo completo no se recomienda a 16 px por sus trazos finos: utilizar el favicon. La carpeta qa incluye las muestras y una lámina de revisión con ampliaciones por píxel; esas ampliaciones muestran el rasterizado deliberadamente.

Mantener proporciones, margen libre y colores. Los avatares incluyen margen para recorte circular. Filosofía: Libertad, Razonamiento y Acompañamiento; observar, comprender y orientar. Elegir corresponde al usuario.

No se modificó el website ni se ejecutaron operaciones Git.

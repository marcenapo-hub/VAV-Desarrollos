# Wireframe landing ON Pacheco — Especificación y guía de handoff

Entregado 2026-09-16. Baja fidelidad, desktop 1440 + mobile 375.
El dibujo original se hizo en Excalidraw; los elementos están guardados en
`wireframe-landing-on-pacheco.elements.json` (ver instrucción al final para
volver a renderizarlo sin rehacerlo).

Este documento es la fuente de verdad del wireframe. Si el wireframe cambia,
se actualiza acá.

---

## Cómo leer el canvas
Tres columnas: desktop 1440 a la izquierda, mobile 375 al centro,
anotaciones a la derecha. Al pie, dos paneles: medición y bloqueantes.

Código de color: blanco = contenido · azul = CTA · amarillo = nota UX/CRO ·
**rojo = asset que no existe todavía**.

---

## Sección 1 — HERO
**Objetivo**: ubicar y calificar en 5 segundos.
**Layout desktop**: imagen full-width 16:9 arriba, H1 + subtítulo abajo a la
izquierda, dos CTA en fila, sello de confianza a la derecha.
**Jerarquía**: H1 24-48 px > subtítulo 14-16 px > CTA > sello.
**Copy**:
- H1: *Cada metro, mejor pensado.* (literal del brochure)
- Sub: *ON Pacheco · Villa Urquiza, CABA · 21 unidades · PB + 5 pisos + 2 retiros*
- Sello: *Planos registrados ante el GCABA*
**CTA**: primario "Ver unidades" (ancla a sección 6) · secundario "Hablar con
el desarrollador" (WhatsApp).
**Assets**: render de fachada — NO EXISTE EN DRIVE.
**Responsive**: render pasa a 4:5; el CTA secundario colapsa en la barra fija
inferior de WhatsApp.
**Notas**: prohibido decir "permiso de obra" u "obra iniciada". Las fotos del
terreno no sirven: son pre-demolición, ago-2025. Sin precio en el hero.

## Sección 2 — MANIFIESTO
**Objetivo**: diferenciar del marketing genérico. Bloque de marca, sin CTA a
propósito.
**Layout**: titular grande + 3 líneas de cuerpo, mucho aire.
**Copy**: *Confort con criterio. La forma sigue a la función. Veintiún
departamentos donde cada decisión de diseño está al servicio de vivir mejor:
plantas resueltas, metros que se usan, materiales que envejecen bien. Sin lujo
impostado.*
**Notas**: tipografía de títulos Manrope. Prohibido por brief: lujo clásico,
premium impostado, greenwashing, minimalismo sin alma, clichés de real estate.

## Sección 3 — CUATRO PILARES
**Objetivo**: argumento racional sin abrir la comparación de amenities.
**Layout**: 4 columnas iguales en desktop, grilla 2x2 en mobile.
1. *21 unidades* — escala boutique, no un edificio de inversión anónimo.
2. *El arquitecto es socio* — Alan Leyendo, MP 33602, firma el proyecto.
3. *Directo a quien construye* — sin intermediario, te contesta el desarrollador.
4. *Planos registrados* — expediente GCABA y terreno propio escriturado.
**Notas**: acá NO va una sección de amenities. ON tiene solárium, parrilla y
jardín en PB; la competencia de Villa Urquiza ofrece pileta, gym, SUM, laundry
y seguridad 24 h. Abrir esa comparación es perderla.

## Sección 4 — EL EDIFICIO: PLANTAS Y TIPOLOGÍAS
**Objetivo**: mostrar el producto de verdad. Núcleo de diferenciación.
**Layout desktop**: 3 columnas — selector de piso (PB, P1-P5, P6, P7) ·
plano grande al centro · ficha de unidad a la derecha.
**Ficha**: tipología, m² propios, balcón/terraza, orientación, estado.
**Datos confirmados**: monoambientes 43-45 m² (12) · 2/3 amb. 74 m² (6) ·
PB con jardín 101,7 m² · 2 amb. + terraza 55,5 a 74 m² (3).
**Assets**: las 21 plantas redibujadas para web — PENDIENTE.
**Responsive**: carrusel con swipe + pinch zoom en el plano.
**Notas**: NO publicar el total de m² del edificio (hay tres cifras distintas
en Drive: 1.050 / 1.200,7 / 1.390,47). Solárium, parrilla y jardín de PB se
mencionan acá, como atributo, no como promesa de complejo.

## Sección 5 — UBICACIÓN
**Objetivo**: validar barrio y conectividad.
**Layout**: mapa 60% + ficha de dirección y entorno 40%.
**Copy**: Pacheco 3026/3028, entre Quesada y Congreso, Villa Urquiza, CABA.
**Notas**: NO inventar distancias a subte, plazas o comercios; que Krak Studio
releve y confirme cada punto. Mapa embebido con carga diferida para no
castigar el LCP.

## Sección 6 — UNIDADES Y DISPONIBILIDAD ⭐
**Objetivo**: NÚCLEO DE CONVERSIÓN.
**Layout desktop**: barra de filtros (Monoambiente / 2-3 amb. / Con terraza /
PB con jardín / Disponible) + tabla con encabezado y una fila por unidad
(Unidad · Piso · Tipología · m² · Orientación · Estado · Acción).
**Responsive**: cards apiladas, chips de filtro con scroll horizontal.
**CTA por fila**: "Consultar" → WhatsApp con mensaje precargado:
*"Hola, me interesa la unidad P1-B (monoambiente, 44 m²) de ON Pacheco.
Quería consultar precio y forma de pago."*
**Banda inferior**: *Solo 2 cocheras para 21 unidades* — única escasez real y
publicable.
**Notas**: SIN precios visibles (decisión comercial). El estado por unidad
debe ser real y mantenido: una unidad marcada disponible que no lo está quema
el lead en el primer mensaje. Usar m² propios, no los m² vendibles de la
planilla interna (criterio propio de VAV, no comparable con el mercado).

## Sección 7 — CÓMO SE COMPRA
**Objetivo**: reductor de fricción n°1 del pozo.
**Layout**: 4 pasos en fila (desktop) / vertical (mobile).
1. *Consulta* — hablás directo con VAV, te mandamos plano y condiciones.
2. *Reserva* — ad referéndum; si VAV no acepta, se devuelve íntegra.
3. *Boleto* — la reserva se imputa al anticipo; precio en dólares.
4. *Obra y posesión* — informe periódico de avance hasta la entrega.
**Notas**: casi ningún competidor explica el proceso. Dato verificable del
modelo de reserva: si VAV no acepta en plazo, reintegro del 100% en 5 días
hábiles sin descuento ni interés. PENDIENTES: monto estándar de reserva y
fórmula del ajuste CAC.

## Sección 8 — VAV DESARROLLOS
**Objetivo**: confianza verificable.
**Layout**: foto a la izquierda, 4 pruebas en lista a la derecha.
**Copy**: *VAV Desarrollos · desarrolladora fundada por Marcelo Napolitano y
el arquitecto Alan Leyendo.*
- Titular del 100% del dominio del terreno, escriturado
- Planos de obra nueva registrados ante el GCABA (21/07/2026)
- Proyecto firmado por profesional matriculado (MP 33602)
- Vendedora: Pacheco 3026 S.A., inscripta en IGJ
**Assets**: foto de equipo u obra — PENDIENTE.
**Notas**: NO hay testimonios ni obras entregadas. Inventar prueba social es
riesgo reputacional y legal: se omite. Micro-CTA acá: *"Avisame cuando abra el
próximo ON"* — siembra la marca paraguas y la lista vale para el desarrollo n°2.

## Sección 9 — PREGUNTAS FRECUENTES
**Objetivo**: matar objeciones sin obligar a preguntar. Acordeón.
1. ¿En qué moneda se paga y cómo se ajustan las cuotas?
2. ¿Qué pasa si la superficie final cambia respecto del plano?
3. ¿Cuándo se entrega? ¿Qué pasa si la obra se demora?
4. ¿Puedo vender o ceder el boleto antes de la entrega?
5. ¿Pago comisión inmobiliaria?
**Respaldo (del boleto modelo)**: precio en dólares billete, desplaza el art.
765 CCyC · tolerancia ±10%, si se supera se ajusta proporcional al m² · si VAV
frena la obra más de 90 días hábiles sin causa el comprador puede intimar y
resolver · cesión permitida con conformidad no denegable sin causa · no hay
comisión, venta directa.
**Notas**: la respuesta de ajuste de cuotas queda en bloque oculto hasta que
se cierre la fórmula CAC. Marcar con schema FAQPage para rich results.

## Sección 10 — CIERRE + FORMULARIO
**Objetivo**: recuperar al que no usó WhatsApp.
**Copy**: *Cuando quieras, te muestro la unidad.* / *Te contesta VAV
Desarrollos, no un intermediario.*
**Campos**: Nombre · WhatsApp · Tipología que te interesa · **¿Es para vivir o
para invertir?**
**Layout**: formulario a la izquierda, botón de WhatsApp al lado con el mismo
peso visual.
**Notas**: 4 campos, sin email (el canal es WhatsApp). El campo vivir/invertir
se queda porque decide cómo responde Marce. Consentimiento Ley 25.326 en una
línea bajo el botón, no checkbox obligatorio.

## Sección 11 — FOOTER LEGAL
VAV Desarrollos · Pacheco 3026 S.A. · Contacto · Instagram.
*Las imágenes son ilustrativas y no contractuales. El proyecto y sus unidades
están sujetos a aprobaciones municipales. Tratamiento de datos conforme
Ley 25.326.*

## Barra sticky mobile
WhatsApp fijo abajo desde que el usuario pasa el hero. Es el atajo para el
tráfico de alta intención que no quiere scrollear hasta la sección 6.
Área táctil mínima 48 px.

---

## Cómo volver a renderizar el wireframe
Los elementos están en `wireframe-landing-on-pacheco.elements.json`.
Para redibujarlo: pasarle el contenido de ese archivo a la herramienta
Excalidraw (`create_view`, parámetro `elements`). El JSON no incluye los
`cameraUpdate` de la sesión original; el dibujo sale igual, sin la animación
de cámara. También se puede reconstruir desde cero leyendo este documento.

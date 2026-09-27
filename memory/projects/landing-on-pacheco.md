# Landing ON Pacheco — Estrategia, arquitectura y wireframe

## Decisiones comerciales de Marce (2026-09-09)
1. **Objetivo de conversión**: WhatsApp con la unidad preseleccionada. Mensaje
   precargado por unidad. El formulario es carril secundario.
2. **Precios**: NO se publican. Solo bajo consulta.
3. **Ajuste del saldo**: por CAC (índice y fórmula a definir).
4. **Orden**: el bloque de unidades va en posición media-baja, después de
   plantas y ubicación.

## Hipótesis de conversión
El comprador de Villa Urquiza enfrenta ~30 proyectos casi indistinguibles,
todos con "Contactar" en el precio y amenities parecidos. No decide por
producto: decide por quién le da certezas. Si la landing muestra el producto
con honestidad técnica poco común y ofrece hablar directo con el dueño en vez
de con un vendedor, conseguimos menos consultas pero mucho más calificadas.

## Propuesta de valor
Un edificio chico donde el arquitecto es socio y el vendedor es el dueño.
21 unidades, no 200. Quien contesta el WhatsApp es quien firma el boleto.

## Segmentos
1. Inversor chico argentino (30-55), 1-2 monoambientes. Ticket bajo.
2. Primer comprador / usuario final joven (28-40). Miedo al pozo.
3. Upgrade familiar (40-55): los 6 de 74 m² y el PB con jardín.

Tensión detectada: el brief apunta a público de diseño, pero el 57% del stock
son monoambientes (producto de renta). Se resuelve con un campo
"vivir / invertir" en el formulario, no con dos landings.

## Arquitectura validada — 11 secciones
1. Hero · 2. Manifiesto · 3. Cuatro pilares · 4. Plantas y tipologías ·
5. Ubicación · 6. Unidades y disponibilidad (núcleo de conversión) ·
7. Cómo se compra · 8. VAV Desarrollos · 9. FAQ · 10. Cierre + formulario ·
11. Footer legal. Más nav sticky y barra fija de WhatsApp en mobile.

**Descartado a propósito**: sección de amenities (perdemos la comparación),
testimonios (VAV no entregó ninguna obra: inventar prueba social es riesgo
reputacional y legal), proyecciones de rentabilidad, contador regresivo,
"últimas unidades" sin stock real, brochure descargable (el que hay es
confidencial), blog.

**Única escasez real y publicable**: 2 cocheras para 21 unidades.

## Copy aprobado (rastreable)
- H1: *"Cada metro, mejor pensado."* → literal del brochure.
- Sub: *"ON Pacheco · Villa Urquiza, CABA · 21 unidades · PB + 5 pisos +
  2 retiros."*
- Sello: *"Planos registrados ante el GCABA."* (formulación obligatoria)
- Manifiesto: *"Confort con criterio. La forma sigue a la función…"*
- Pilar: *"Comprás directo a quien construye."* (tono sobrio, no oferta)
- Cierre: *"Cuando quieras, te muestro la unidad. Te contesta VAV
  Desarrollos, no un intermediario."*
- WhatsApp precargado: *"Hola, me interesa la unidad P1-B (monoambiente,
  44 m²) de ON Pacheco. Quería consultar precio y forma de pago."*

## Medición
Conversiones: `lead_whatsapp` (con parámetro de unidad y sección de origen),
`lead_form`, `lead_proximo_on`.
Micro: `view_unidades`, `select_unidad`, `view_planta`, `faq_open`, `scroll_75`.
Semanal: % que llega a la sección 6 (si es bajo, el orden elegido está
costando conversión) · unidad más consultada vs. stock real · leads por
tipología vivir/invertir.

## Oportunidad de largo plazo
La landing debe construirse como **plantilla del sistema ON**, reutilizable
para el próximo "ON + [calle]". Incluir micro-CTA "avisame cuando abra el
próximo ON": esa lista vale plata en el desarrollo n°2.

## Entregado
- 2026-09-16: wireframe de baja fidelidad en Excalidraw, desktop 1440 y
  mobile 375, 11 secciones, con anotaciones UX/CRO, panel de medición y
  panel de bloqueantes. Falta la guía de handoff escrita para el diseñador.

---

# ESTADO DEL TRABAJO — leer esto primero al retomar

**Última actualización: 2026-09-27.**

## Dónde estamos
Etapas A (investigación en Drive), B (estrategia), C (arquitectura de
información) y D (wireframe) **cerradas y validadas por Marce**.
La landing NO está diseñada ni desarrollada todavía.

## Entregado
- Ficha del proyecto verificada contra Drive → `on-pacheco.md`
- Estrategia, arquitectura y decisiones comerciales → este archivo
- Wireframe desktop + mobile, 11 secciones → `wireframe-landing-on-pacheco.md`
  (especificación completa y guía de handoff) y
  `wireframe-landing-on-pacheco.elements.json` (para volver a renderizarlo)

## Próximo paso, en orden
1. **Conseguir los renders de Alan.** Es el bloqueante duro: sin fachada +
   2 interiores no se puede diseñar. Tema para la reunión semanal de VAV
   (jueves 15:30). Pedirle también la memoria descriptiva de terminaciones
   (Anexo II del boleto).
2. Definir los datos que faltan: monto de reserva, fórmula del ajuste CAC,
   fecha estimada de inicio de obra, disponibilidad real por unidad,
   WhatsApp comercial, dominio.
3. Pasarle a Krak Studio el paquete de handoff:
   `wireframe-landing-on-pacheco.md` + el canvas + la lista de assets.
   **Sin** `ON_Pacheco_Precios.xlsx` ni `On Pacheco.pdf`.
4. Que Krak Studio releve y confirme los puntos del entorno para la sección
   de ubicación (no inventar distancias).
5. Diseño visual → desarrollo → medición.

## Lo que NO hay que volver a discutir (ya decidido)
- Conversión por WhatsApp con unidad preseleccionada.
- No se publican precios.
- Ajuste de cuotas por CAC.
- Bloque de unidades en posición media-baja.
- Arquitectura de 11 secciones, con las exclusiones justificadas.
- En comunicación pública: "planos registrados ante el GCABA", nunca
  "permiso de obra" ni "obra iniciada".

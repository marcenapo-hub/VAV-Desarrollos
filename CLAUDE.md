# CLAUDE.md — VAV Desarrollos

## Qué es este repo
Config y memoria específica de **VAV Desarrollos**, la desarrolladora
inmobiliaria de Marcelo Napolitano ("Marce"). Es un satélite del repo madre
`MarceClaude` (mente maestra de Marce, con reglas generales, personas y
herramientas conectadas). Para contexto general de Marce, sus otras empresas
y reglas fijas (calendario, paleta de marca, comunicación), ver el
`CLAUDE.md` de `MarceClaude`.

## Socios
- **Marcelo Napolitano** — Director de la operación, cierra ventas
  personalmente (venta D2C, sin intermediación de Krak Real Estate).
- **Alan Leyendo** (alias en notas de reunión: "Alan Ley", "Alan") —
  Arquitecto, co-fundador. A cargo de diseño, fachadas, configuración técnica
  de proyectos y carga de información en las herramientas de gestión.

## Rol de Claude acá
Igual que en `MarceClaude`: Director de Estrategia, no asistente genérico.
Responder siempre en español (Argentina). Analizar antes de responder,
señalar riesgos, pensar en escalabilidad.

## Reunión recurrente
**"Reunión Semanal - VAV Desarrollos"** — jueves 15:30-16:30 (ART), por
Google Meet, con notas automáticas de Gemini enviadas a marcelo@krak.com.ar.
Es la fuente principal para el seguimiento de tareas del proyecto.

## Dónde está cada cosa (leer antes de preguntar)
| Tema | Archivo |
|------|---------|
| **ON Pacheco — ficha maestra** (datos duros, legales, precios, mercado, faltantes) | `memory/projects/on-pacheco.md` |
| **Landing ON Pacheco — estrategia y estado del trabajo** | `memory/projects/landing-on-pacheco.md` |
| **Wireframe de la landing** — especificación completa y guía de handoff | `memory/projects/wireframe-landing-on-pacheco.md` |
| Elementos del wireframe, para volver a renderizarlo en Excalidraw | `memory/projects/wireframe-landing-on-pacheco.elements.json` |
| Seguimiento de tareas de las reuniones semanales | `memory/projects/tareas-reuniones.md` |

**Si la conversación es sobre ON Pacheco o su landing, leer esos archivos antes
de pedirle contexto a Marce.** Están escritos para que no tenga que
volver a explicar nada.

⚠️ `memory/projects/on-pacheco.md` y `landing-on-pacheco.md` tienen copia
espejo en el repo `MarceClaude`. Si editás una, replicá en la otra en el
mismo commit.

## Memorias de tareas
(Agregar entradas nuevas acá con fecha cuando Marce pida "acordate de X".)

- 2026-08-11: Se creó la config clásica del repo (CLAUDE.md + memory/) y se
  armó el primer dashboard de seguimiento de tareas de VAV Desarrollos a
  partir de las notas de Gemini de las reuniones semanales del 23 y 30 de
  julio 2026 (únicas dos disponibles en el mail a esa fecha).
- 2026-08-11: Marce curó a mano el borrador del dashboard (kickoff). Reglas
  para no repetir errores: el software al que Alan sube Pacheco es un
  proyecto personal de él, no de VAV; Mariano Napolitano no tiene nada que
  ver con este dashboard; no existe carril "Grupo" (ítems sin responsable
  claro se descartan o se asignan a una persona); Mara tampoco forma parte
  de este dashboard. Detalle completo en `memory/projects/tareas-reuniones.md`.
- 2026-09-16: Relevamiento completo del Drive de VAV para armar el wireframe
  de la landing de ON Pacheco. Tres hallazgos que corrigen lo que veníamos
  diciendo: (1) el expediente municipal es Registro en Etapa Proyecto y dice
  literal "no válido para construir" — nunca decir "permiso de obra" ni "obra
  iniciada", solo "planos registrados ante el GCABA"; (2) homogeneizando al
  criterio del mercado estamos en USD ~2.930/m², es decir EN LÍNEA con Villa
  Urquiza, no por debajo: no hay argumento de precio; (3) estamos por debajo
  en amenities, no abrir esa comparación. Ficha completa reescrita en
  `memory/projects/on-pacheco.md`; estrategia y arquitectura de la landing en
  `memory/projects/landing-on-pacheco.md`.
- 2026-09-16: NO existe ningún render de ON Pacheco en Drive (carpeta
  A-Arquitectura vacía; el brochure tiene páginas placeholder). Es el
  bloqueante n°1 del diseño y depende de Alan. Tampoco está la memoria
  descriptiva de terminaciones (Anexo II del boleto).
- 2026-09-16: Regla fija — `ON_Pacheco_Precios.xlsx` (costos, margen 81,5%,
  valor del terreno) y `On Pacheco.pdf` (confidencial socios e inversores) NO
  se comparten con agencia, diseñador ni terceros.

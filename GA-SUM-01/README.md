# GA-SUM-01 · PE-U1 — Ingeniería de Requisitos y Proceso de Requisitos

**Asignatura:** Ingeniería de Requerimientos (ISR-401)  
**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Carrera:** Ingeniería de Software, cuarto nivel «B»  
**Período:** 2026–2027 SPA  
**PFC:** Plataforma de Ventas con módulo de recomendación basado en IA para el soporte de ventas en establecimientos eléctricos  
**Estado de esta copia:** Contexto y fundamento te'orico inicial (Winston + Alberto), pendientes de validaci'on.

## Integrantes y responsabilidades previstas

| Integrante | Aporte de la primera jornada |
|---|---|
| **Cedeño Avila Winston Damian** | Contexto y límites del PFC; coordinación de secciones |
| **Paca Pilataza Luis Alberto** | Fundamento teórico, fuentes primarias y ejemplos del PFC |
| **Rivera Suarez Jonathan Javier** | Actores, matriz poder/interés, contexto y framework preliminar |

El reparto de tareas se propone para revisión y aprobación del grupo. Cada integrante debe revisar su contenido y realizar el commit desde su cuenta una vez que efectivamente haya trabajado su aporte. No se atribuyen entrevistas ni mediciones no ejecutadas.

## Tema y enfoque

Se analiza el PFC de una plataforma para apoyar ventas de materiales eléctricos mediante catálogos, inventario, trazabilidad de operaciones y recomendaciones de productos basadas en IA. Se toma como referencia el contexto comercial local de Quevedo (ELECTRORIOS), pero **ninguna integración, política interna ni entrevista se declara verificada**. Se diferencia lo observado de lo supuesto y de lo que requiere autorización.

## Archivos actuales en este avance

- `main.tex`: documento maestro en formato IEEE.
- `main.pdf`: PDF generado mediante `pdflatex` y `biber`.
- `referencias.bib`: referencias bibliográficas primarias y verificables.
- `secciones/00_contexto_pfc.tex`: sección 0, alcance, necesidades y preguntas.
- `secciones/01_fundamento.tex`: fundamento 2.1–2.4 y ejemplos aplicados.

## Compilación reproducible

Se requiere TeX Live o MiKTeX con `IEEEtran`, `babel` español, `biblatex` estilo IEEE, `biber`, `microtype`, `lmodern`, `booktabs`, `tabularx`, `xurl` y `hyperref`. Desde la carpeta `GA-SUM-01`:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
biber main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Los comandos se han probado para la versión entregada. No incluir archivos de compilación auxiliares (`.aux`, `.bbl`, `.blg`, `.log`).

## Rúbrica y alcance del trabajo

Según la rúbrica reducida, la entrega final exigirá al menos **15 requisitos** identificados y justificados, RNF cuantificados, revisión argumentada de propiedades IEEE 29148, roles de IR, trazabilidad y artefactos de elicitación/análisis/especificación/validación. La guía experimental ampliada incluye también el fundamento 2.1–2.6, ocho perspectivas, mapa conceptual editable, fuentes primarias, conclusiones y un informe de mínimo 15 páginas.

**Este paquete es un avance de la jornada del 12 de noviembre; todavía no es la entrega final ni demuestra entrevistas realizadas.**

## Plan para los días restantes

- **Viernes 13/11:** completar taxonomía y matriz de al menos 15 requisitos con criterios de aceptación, mejorar fuentes, preparar ocho perspectivas y los artefactos del proceso.
- **Sábado 14/11:** validar coherencia y trazabilidad, integrar diagramas y anexos auténticos, redactar conclusiones revisadas por sus autores y compilar el documento completo.

Las fechas son un plan, no commits preprogramados. La fecha límite de esta práctica debe comprobarse en el SGA.

## Fuentes utilizadas

Consultar `referencias.bib`. Se identifican principalmente ISO/IEC/IEEE 29148:2018, ISO/IEC 25010:2023, Pohl (segunda edición, 2025), SWEBOK v4 (2024), PMBOK 7 (2021), las ediciones pedidas por la guía de 15288 y 12207, Glinz (2007) y EARS (2009). La edición 12207:2017 se conserva por exigencia de la guía aunque tiene una edición posterior; no se considera la versión vigente.

## Uso de IA e integridad

Se utilizó ChatGPT (OpenAI, GPT-6) como apoyo en la organización, los borradores y la compilación en LaTeX. Las afirmaciones técnicas y los enlaces bibliográficos se cotejaron con fuentes oficiales cuando estaban disponibles. Cada integrante debe verificar, comprender y adaptar su sección antes de publicarla. No deben atribuirse a terceros trabajos o validaciones no realizadas.

## Actualización de actores y contexto — 13 de noviembre de 2026

Se incorpora el apartado de actores, matriz de poder e interés, relaciones externas y actividades del proceso. Este contenido estaba previsto para el avance de Rivera del día anterior, pero se integró desde la cuenta de Winston el **13 de noviembre**, por estar pendiente su publicación. No se modifica el historial ni se presenta como un commit realizado por Rivera. El equipo todavía debe revisar y validar este borrador. El PDF del avance se puede generar desde `main.tex` y las fuentes; la publicación del binario en GitHub queda pendiente.

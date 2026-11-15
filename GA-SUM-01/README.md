# GA-SUM-01 — Práctica Experimental Unidad I

Ingeniería de Requisitos — Software, cuarto nivel B — UTEQ — 2026–2027 SPA.

**Proyecto:** Plataforma de Ventas con módulo de recomendación basado en IA para el soporte de ventas en establecimientos eléctricos.

**Estado:** Revisión argumentada de los requisitos incorporada; mapa y síntesis pendientes.

## Integrantes

| Integrante | Responsabilidad en la planificación de esta jornada |
|---|---|
| Cedeño Avila Winston Damian | Integración del proceso, guion de elicitación y casos de validación |
| Paca Pilataza Luis Alberto | Revisión individual de la calidad de los 16 requisitos y trazabilidad |
| Rivera Suarez Jonathan Javier | Mapa conceptual, síntesis y organización de evidencias |

La distribución describe los entregables preparados; cada persona debe comprobar y asumir su propio aporte antes de subirlo. Los archivos fueron elaborados como propuestas de práctica, no como resultados de entrevistas realizadas.

## Estructura del informe

`main.tex` integra el contexto del PFC, el fundamento de Ingeniería de Requisitos, los actores, el proceso, 16 requisitos, ocho perspectivas, artefactos de validación y los apartados añadidos en cada avance.

- `secciones/00_contexto_pfc.tex`: descripción, límites, visión y necesidades.
- `secciones/01_fundamento.tex`: fundamentos y tipos de requisitos.
- `secciones/02_actores_contexto.tex`: interesados y framework.
- `secciones/03_proceso_aplicado.tex`: aplicación documental de actividades.
- `secciones/04_matriz_requisitos.tex`: 16 requisitos, métricas y control de calidad.
- `secciones/05_perspectivas_contexto.tex`: ocho perspectivas de Pohl y modelo ER.
- `secciones/06_artefactos_proceso.tex`: guion, conflictos y validación por preparar.
- `secciones/07_revision_calidad.tex`: revisión argumentada, fuentes y decisiones pendientes.

- `figuras/diagrama_er_pfc.drawio` y `.png`: modelo ER proporcionado por el grupo.

- `anexos/`: guiones, casos de validación y registro de fuentes y evidencias.
- `referencias.bib`: fuentes bibliográficas IEEE y documentos del caso.

## Compilación

Requiere TeX Live o MiKTeX con IEEEtran, babel español, biblatex, biber, graphicx, booktabs, tabularx y hyperref. Situarse en `GA-SUM-01`:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
biber main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

El documento compilado se llama `main.pdf`. Mantener las carpetas `figuras` y `secciones` junto al archivo principal. No subir archivos auxiliares `.aux`, `.bbl`, `.log` o `.bcf`.

## Criterios de evaluación

La rúbrica reducida exige al menos 15 requisitos distintos, cinco de calidad medibles, revisión de sus propiedades, actores y marco de IR, evidencia de las cuatro actividades principales, fuentes IEEE y figuras numeradas. La guía completa añade ocho perspectivas de Pohl, mapa conceptual editable, cinco conclusiones de al menos 80 palabras y 15 páginas de contenido.

## Fuentes y contexto

Se consultaron fichas oficiales de ISO/IEC/IEEE 29148:2018, ISO/IEC 25010:2023, Springer para Pohl, SWEBOK v4 e IREB. La base del problema y el diagrama ER fueron aportados por el equipo. Las afirmaciones sobre la operación de ELECTRORIOS deben validarse con la organización antes de presentarlas como hallazgos comprobados.

## Uso de IA

ChatGPT se empleó como apoyo para preparar borradores y ordenar el trabajo en LaTeX. Los integrantes manifiestan haber revisado la redacción de sus avances y contrastado la información bibliográfica con fuentes oficiales. Cada nueva sección debe comprobarse y, de ser necesario, corregirse por el integrante responsable antes del commit. No se atribuyen a terceros entrevistas, pruebas o decisiones no realizadas.

## Evidencias todavía necesarias

- Autorización y registro verificable de entrevistas u observaciones reales, si se realizaron.
- Captura genuina de la biblioteca Zotero o Mendeley para el Anexo B, exigida por la guía.
- Confirmación en el SGA de la fecha, modalidad de entrega y condiciones específicas.
- Revisión por el equipo de las cinco conclusiones temáticas; la guía dice también «una por integrante», pese a que el equipo está conformado por tres personas.

## Publicación y autoría

Los ZIP son paquetes de avance y no commits publicados. Deben subirse en orden, cada uno desde la cuenta que realiza realmente la revisión y publicación. Los mensajes seguirán el prefijo `docs:`. No deben modificarse fechas históricas ni atribuirse a alguien una publicación hecha por otra persona.

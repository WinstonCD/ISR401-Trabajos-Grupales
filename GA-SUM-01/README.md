# GA-SUM-01 — Práctica Experimental Unidad I

**Ingeniería de Requisitos · UTEQ · Software 4.º B · SPA 2026–2027**

**PFC:** Plataforma de Ventas con módulo de recomendación basado en IA para el soporte de ventas en establecimientos eléctricos.

**Estado:** informe documental finalizado y compilable. Los requisitos, las reglas del negocio y las pruebas siguen siendo propuestas pendientes de validación en campo; no se afirma que el sistema esté implementado ni que las entrevistas se hayan realizado.

## Equipo

- **Cedeño Avila Winston Damian:** análisis documental, proceso, guion de elicitación y casos de prueba.
- **Paca Pilataza Luis Alberto:** matriz de 16 requisitos, evaluación de propiedades, métricas y trazabilidad.
- **Rivera Suarez Jonathan Javier:** contexto, ocho perspectivas, modelo entidad-relación y mapa conceptual.

Las funciones describen el trabajo organizado por el equipo; el historial de GitHub refleja quién publica efectivamente cada commit.

## Contenido del informe

- Identificación del PFC, problema y cinco partes interesadas.
- Fundamentos de requisitos basados en ISO/IEC/IEEE 29148, Pohl y SWEBOK v4.
- **16 requisitos únicos**, incluidos cinco de calidad con objetivos medibles.
- Actores, actividades principales y transversales del proceso de requisitos.
- Revisión de las características de calidad de los requisitos y matriz de trazabilidad.
- Ocho perspectivas de contexto de Pohl y modelos aplicados al sistema de ventas.
- **Figura 1:** mapa conceptual integrador, con al menos tres conexiones cruzadas. Fuente editable en `figuras/mapa_conceptual.drawio` y PNG.
- **Figura 2:** diagrama entidad-relación del PFC, con fuente editable en `figuras/diagrama_er_pfc.drawio` y PNG.
- **Cinco conclusiones temáticas**, de al menos 80 palabras cada una.
- **Anexo A:** exportación de Zotero en estilo IEEE, con 13 registros. Se conserva el RTF original y una versión LaTeX que aparece en el PDF compilado.
- **Anexo B:** captura genuina de la colección Zotero `GA-SUM-01` con 13 referencias. Se conserva la imagen original y un recorte de lectura.

## Estructura

- `main.tex`: archivo maestro IEEE.
- `referencias.bib`: fuentes citadas durante el análisis.
- `secciones/`: contexto, fundamento, requisitos, perspectivas, proceso, calidad, mapa, trazabilidad y conclusiones.
- `figuras/`: mapa conceptual editable y diagrama ER, PNG y draw.io; recorte de Zotero.
- `anexos/`: guion de entrevistas, casos de prueba, revisión y anexos bibliográficos.

## Compilar el PDF

Instalar TeX Live o MiKTeX con `IEEEtran`, `biblatex`, `biber`, `graphicx`, `booktabs`, `tabularx`, `hyperref` y `xurl`. Desde `GA-SUM-01` ejecutar:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
biber main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

El resultado es `main.pdf`, que debe incluir las dos figuras del PFC, los Anexos A y B, y la declaración de uso de IA al final. Evitar subir archivos auxiliares `.aux`, `.log`, `.bcf`, `.bbl` y `.run.xml`.

## Bibliografía y trazabilidad

Las fichas oficiales de ISO/IEC/IEEE se conservan cuando no hay DOI o se exige una edición específica. La bibliografía analítica incluye dos artículos de 2022 con DOI: `10.1007/s00766-022-00383-7` y `10.1007/s00766-021-00367-z`. El Anexo A refleja fielmente las **13 referencias registradas en Zotero al momento de exportar** y conserva las fuentes antiguas que estaban en la biblioteca; por eso no es idéntico al listado dinámico generado desde `referencias.bib`.

## Alcance y evidencia

La práctica aplica el proceso sobre la base escrita del proyecto y el diagrama ER del equipo. Los guiones y casos de validación son artefactos preparados, **no entrevistas ni pruebas efectuadas**. Si el docente exige evidencias de trabajo de campo, tendrán que obtenerse en una fase posterior con autorización del establecimiento. La entrega efectiva y el horario de cierre deben comprobarse en el SGA.

## Uso de IA

ChatGPT apoyó la preparación de borradores y la organización técnica en LaTeX. El grupo informó haber revisado sus borradores y comprobado los datos con fuentes oficiales. Ninguna ayuda sustituye la revisión y responsabilidad académica de los integrantes.

## Publicación

Este es un paquete fuente para el commit documental de cierre; no modifica por sí solo el repositorio. Reemplazar únicamente los archivos correspondientes en `GA-SUM-01`, compilar `main.pdf` desde las fuentes y publicarlo en GitHub. Mensaje sugerido: `docs: integrar anexos de Zotero y cerrar informe del PFC`.

# GA-PRAC-01 — Modelos de proceso de requisitos

**Grupo del SGA:** CPR · **Asignatura:** Ingeniería de Requisitos (ISR-401) · **Carrera:** Software, cuarto nivel «B»

**Caso usado:** sistema de un GAD con contrato público, tomado como *escenario académico provisional* de la guía FORM-PC-01. **No se ha confirmado que sea el escenario oficialmente asignado al grupo CPR.** No se analizaron contratos, GAD ni entrevistas reales.

## Integrantes registrados en el SGA

- Cedeño Ávila Winston Damián
- Paca Pilataza Luis Alberto
- Rivera Suárez Jonathan Javier

El registro de integrantes no demuestra su participación. Solo se atribuye trabajo a quien realmente revise, modifique o publique sus aportes; cualquier ausencia debe comunicarse al docente.

## Documentos

- `main.tex`: fuente editable IEEEtran a una columna.
- `main.pdf`: PDF generado desde el mismo archivo fuente.
- `referencias.bib`: referencias IEEE.

## Cómo compilar en un entorno con TeX Live

Desde esta carpeta, ejecutar en orden:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
biber main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Dependencias: `IEEEtran`, `babel` (español), `biblatex`, `biber`, `lmodern`, `microtype`, `csquotes`, `longtable`, `tabularx`, `array`, `booktabs`, `enumitem`, `needspace`, `geometry`, `hyperref` y paquetes TeX habituales.

## Alcance del sexto avance (versión consolidada)

Reúne caracterización, criterios y matriz contextualizada, actores posibles, actividades centrales y transversales del framework de IR, recomendación con razones y descarte de alternativas, riesgos y mitigaciones, y ejemplo académico de trazabilidad. Incluye una nota de límites del caso y declaración de apoyo de IA.

**Revisión antes de entregar:** comprobar compilación y lectura del PDF; confirmar con el docente si el GAD es el escenario válido para CPR; verificar participación real de los miembros; comprobar la rúbrica exacta del SGA, la entrega solicitada y que la bibliografía sea fiel a las fuentes. Un commit por sí solo no acredita participación si no refleja trabajo efectivo.

## Referencias contrastadas

- Klaus Pohl, *Requirements Engineering*, Springer, 2.ª ed. (2025): ISBN 978-3-662-69204-2.
- IREB CPRE Foundation Level Syllabus 3.3.0 (2026), autores Bühne, Glinz, van Loenhoud y Staal.
- ISO/IEC/IEEE 29148:2018, norma de ingeniería de requisitos.

Los detalles están en `referencias.bib`.

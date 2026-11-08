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

## Alcance del quinto avance

Incorpora una **recomendación argumentada** del modelo iterativo con controles formales, contrasta por qué no se eligen cascada y ágil como modelos principales y presenta riesgos concretos y mitigaciones. Conserva los modelos, matriz y framework de avances anteriores.

**Pendiente para la revisión final:** incorporar una comprobación más detallada de la trazabilidad, revisar coherencia y fuentes con el compañero y confirmar las condiciones de entrega del SGA. La propuesta no demuestra hechos reales de contratación pública.

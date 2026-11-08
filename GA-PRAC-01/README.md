# GA-PRAC-01 · Grupo CPR

**Asignatura:** Ingeniería de Requerimientos (ISR-401) · 4.º nivel «B».  
**Avance:** 4 de 6 · Actores y framework de ingeniería de requisitos.

**Formato:** IEEEtran, una columna, títulos numerados, tablas y referencias IEEE; mismo criterio visual del trabajo FORM-TL-01 del repositorio individual.  
**Escenario utilizado:** sistema de un GAD con contrato público. **Caso de estudio provisional elegido de las opciones de FORM-PC-01; no consta como escenario asignado oficialmente al grupo.**

## Integrantes registrados en el SGA

- Cedeño Ávila Winston Damián
- Paca Pilataza Luis Alberto
- Rivera Suárez Jonathan Javier

El registro de integrantes no equivale a constancia de participación. Los aportes efectivos se deben verificar mediante revisión individual y commits de cada integrante. La situación del tercer integrante debe comunicarse al docente sin atribuirle trabajo que no haya hecho.

## Contenido del cuarto avance

- `main.tex`: caracterización, matriz comparativa y propuesta de actores, actividades y artefactos del framework de IR.
- `main.pdf`: documento generado desde el LaTeX.
- `referencias.bib`: bibliografía utilizada, en formato IEEE; sin cambios respecto del avance anterior.

El cuarto avance mantiene la matriz del tercer commit y añade un mapeo de actores, actividades y artefactos. La matriz estudia siete criterios: estabilidad y cambios, stakeholders, tipo de sistema e integración, riesgo y criticidad, documentación y trazabilidad, validación y entrega, y condiciones de aplicación. Los supuestos son exclusivamente didácticos: no se obtuvieron contratos, pliegos ni entrevistas de un GAD real.

## Compilación

Con TeX Live o MiKTeX (IEEEtran, babel en español, biblatex, biber y paquetes de tablas), ejecutar en la carpeta del documento:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
biber main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

La selección definitiva del escenario debe verificarse con el docente. La actividad FORM-PC-01 individual y la GA-PRAC-01 grupal del SGA tienen instrucciones distintas; no se deben confundir sus formatos de entrega.

## Uso de herramientas

Se utilizó ChatGPT como apoyo para estructurar el borrador, redactar la comparación y revisar LaTeX. El contenido debe ser revisado y explicado por sus autores; no se deben inventar pruebas o participaciones.

## Alcance de este avance

Se identifican actores posibles (responsable institucional, ventanilla, tecnologías, contratación/jurídica, proveedor y ciudadanía), actividades centrales (elicitación, documentación, validación y negociación) y transversales (gestión de cambios, trazabilidad y priorización). Son **supuestos académicos** que requieren confirmación; no se realizaron entrevistas, contratos ni aprobaciones. Este cuarto avance fue preparado para revisión de Winston; no acredita por sí solo participación de los demás integrantes.

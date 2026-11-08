# GA-PRAC-01 · CPR

**Materia:** Ingeniería de Requerimientos (ISR-401) · 4.º nivel «B».  
**Escenario de esta versión:** Sistema de un GAD con contrato público. **Caso de estudio provisional elegido de la guía; no está confirmado como escenario asignado por el docente.**

Integrantes registrados en el SGA: Cedeño Ávila Winston Damián, Paca Pilataza Luis Alberto, Rivera Suárez Jonathan Javier.

Trabajo organizado entre Winston y Luis Alberto. La participación real se acredita por sus propias revisiones, aportes y commits. Sobre el tercer integrante se debe consultar al docente; no se inventan participaciones.

## Documento

- `main.tex`: fuente del documento; etapa **2 de 6**.
- `main.pdf`: archivo compilado desde la fuente y optimizado para lectura. La compilación reproduce el contenido y la distribución, aunque la compresión posterior puede modificar los bytes.
- `referencias.bib`: bibliografía IEEE.

## Compilación reproducible

Se necesita TeX Live o MiKTeX con IEEEtran, babel español, biblatex, biber y paquetes habituales de tablas.

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
biber main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

## Integridad académica

La matriz usa hipótesis didácticas expresas, no entrevistas ni datos reales de una institución. El escenario y la explicación final son responsabilidad del grupo. No presentar un contenido como aporte de otro estudiante sin su revisión efectiva. Se declara el apoyo de ChatGPT en el documento final.

**Diferencia importante:** El PDF FORM-PC-01 entregado como referencia describe una actividad individual; no se aplica automáticamente su regla de PDF de una sola página a la actividad grupal GA-PRAC-01 del SGA. Verificar en el SGA el formato de entrega.

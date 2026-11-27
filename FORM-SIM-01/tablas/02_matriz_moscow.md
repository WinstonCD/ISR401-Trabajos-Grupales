# 02. Matriz MoSCoW — propuesta inicial

**Estado:** propuesta para la negociación grupal; no es acuerdo final hasta que los roles la aprueben.

| ID | Requisito resumido | Propuesta | Justificación para la discusión |
|---|---|---|---|
| R01 | Acceso con credenciales institucionales | **Must** | Controla el acceso a información académica personal y permite identificar al estudiante que realiza la inscripción. |
| R02 | Consulta de oferta académica y cupos | **Must** | El estudiante necesita conocer las asignaturas disponibles para tomar una decisión de inscripción. |
| R03 | Selección y envío de solicitud de inscripción | **Must** | Es la función central del sistema; sin ella no se realiza el proceso de inscripción. |
| R04 | Validación de prerrequisitos y cupos | **Must** | Evita confirmar solicitudes que incumplen reglas académicas o exceden la capacidad disponible. |
| R05 | Advertencia de cruces de horario | **Should** | Reduce errores y conflictos de horario; el grupo debe decidir si la validación automática es necesaria desde la primera versión. |
| R06 | Consulta de historial académico | **Should** | Ayuda al estudiante a planificar, aunque puede existir una consulta institucional separada mientras se completa la primera versión. |
| R07 | Consulta de obligaciones financieras/bloqueos | **Should** | Es importante para aplicar restricciones institucionales, pero la integración con el registro financiero puede aumentar el esfuerzo. |
| R08 | Notificación del resultado | **Could** | Mejora la comunicación, pero el resultado también podría consultarse dentro del sistema en la primera versión. |
| R09 | Descarga de comprobante | **Could** | Es útil como respaldo, aunque la confirmación en pantalla puede cubrir inicialmente la necesidad básica. |
| R10 | Reportes administrativos agregados | **Won't (por ahora)** | Se propone dejarlo fuera de la primera versión para concentrar el esfuerzo en completar el flujo de inscripción del estudiante. Puede revisarse en una versión posterior. |

## Comprobación del límite de esfuerzo de Must

Para verificar que el conjunto Must no supere el 60 % del esfuerzo estimado, se usa una estimación relativa en puntos de esfuerzo (no horas):

| ID | Categoría propuesta | Puntos de esfuerzo |
|---|---|---:|
| R01 | Must | 8 |
| R02 | Must | 7 |
| R03 | Must | 14 |
| R04 | Must | 10 |
| R05 | Should | 8 |
| R06 | Should | 7 |
| R07 | Should | 9 |
| R08 | Could | 3 |
| R09 | Could | 2 |
| R10 | Won't | 12 |
| **Total** |  | **80** |

Esfuerzo Must = 8 + 7 + 14 + 10 = **39 puntos**.  
Porcentaje Must = 39 / 80 × 100 = **48,75 %**.  
La propuesta se mantiene por debajo del máximo del 60 %.

Estas estimaciones son relativas y deben ser aceptadas o ajustadas por el grupo. Si cambia una prioridad o una estimación, recalculen el porcentaje. No presenten estos puntos como mediciones reales de desarrollo.

## Registro de aprobación

- Fecha de negociación: ____________________
- Must aprobados por el grupo: ____________________
- Cambios respecto de esta propuesta: ____________________
- Responsable de actualizar la tabla: ____________________

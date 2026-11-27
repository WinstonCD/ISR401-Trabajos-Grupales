# 01. Catálogo propuesto de diez requisitos

**Caso:** sistema de inscripciones universitarias.  
**Estado:** propuesta inicial para contrastar con las tarjetas oficiales entregadas por el docente.

| ID | Requisito candidato | Criterio de comprobación propuesto |
|---|---|---|
| R01 | El sistema permitirá que un estudiante acceda usando sus credenciales institucionales. | Una cuenta institucional válida inicia sesión y una credencial inválida no permite acceder. |
| R02 | El sistema mostrará la oferta de asignaturas del período vigente, incluyendo código, nombre, créditos, horario y cupos disponibles. | El estudiante puede consultar esos datos para las asignaturas publicadas del período. |
| R03 | El sistema permitirá al estudiante seleccionar asignaturas y enviar una solicitud de inscripción para el período vigente. | La solicitud registra el período y las asignaturas seleccionadas por el estudiante autenticado. |
| R04 | Antes de confirmar una inscripción, el sistema verificará los prerrequisitos y los cupos disponibles de cada asignatura seleccionada. | Una asignatura sin prerrequisitos cumplidos o sin cupo no queda confirmada y se informa el motivo. |
| R05 | El sistema advertirá cuando las asignaturas seleccionadas tengan cruces de horario. | La revisión identifica los intervalos horarios superpuestos antes de confirmar la inscripción. |
| R06 | El sistema permitirá al estudiante consultar su historial académico. | Se muestran las asignaturas y estados académicos que consten en el registro institucional disponible. |
| R07 | El sistema permitirá consultar si el estudiante tiene obligaciones financieras o bloqueos que afecten su inscripción. | Se muestra el estado disponible en el registro financiero institucional; este requisito no presupone implementar pagos en línea. |
| R08 | El sistema notificará al estudiante el resultado de su solicitud de inscripción. | Se genera una notificación cuando la solicitud cambia a un estado definitivo. |
| R09 | El sistema permitirá descargar un comprobante de inscripción con estudiante, período y asignaturas confirmadas. | El documento descargado contiene los datos de la inscripción confirmada. |
| R10 | El sistema permitirá a usuarios administrativos autorizados consultar reportes agregados de inscripciones por período y asignatura. | Un usuario autorizado puede consultar totales agregados del período seleccionado. |

## Observaciones

- Estos requisitos se redactaron como candidatos para hacer operativa la simulación; no se afirma que sean las tarjetas oficiales.
- Si las tarjetas del docente presentan otros requisitos, nombres o prioridades, prevalecen esas tarjetas. Actualicen esta tabla y las demás matrices de forma consistente.
- No se agregan integraciones de pago, políticas institucionales ni reglas académicas que no hayan sido confirmadas.

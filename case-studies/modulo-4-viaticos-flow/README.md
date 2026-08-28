# Viáticos Flow — Módulo 4

## Resumen

Viáticos Flow es una propuesta de rediseño del proceso de solicitud y aprobación de viáticos corporativos. El caso aplica Service Design y Design Thinking para reemplazar el uso de planillas y correos dispersos por un flujo digital más simple, claro, trazable y confiable.

## Problema

El proceso actual genera dudas sobre los campos obligatorios, errores en montos y respaldos, incertidumbre sobre el envío y poca visibilidad del estado de cada trámite. Esto provoca correcciones, demoras y consultas manuales frecuentes.

## Usuario principal

**Luis**, colaborador de 32 años que solicita viáticos para viajes laborales. Necesita completar el trámite correctamente desde la primera vez y consultar su estado sin depender de correos o planillas.

| Necesidad | Dolor actual |
|---|---|
| Completar la solicitud rápido | No sabe qué campos son obligatorios |
| Enviar información correcta | Teme equivocarse en monto o respaldo |
| Consultar el estado del trámite | Debe preguntar o revisar correos dispersos |
| Obtener confirmación | No sabe si la solicitud fue enviada correctamente |

## Insight y reto de diseño

**Insight:** Luis necesita un flujo simple y visible en todo momento porque quiere enviar su solicitud correctamente desde la primera vez y evitar perder tiempo corrigiendo errores.

**How Might We:** ¿Cómo podríamos simplificar la solicitud de viáticos para que el colaborador la complete rápido y sin errores? ¿Cómo podríamos mostrar el estado del trámite en un solo lugar para reducir la incertidumbre?

## Service Blueprint

| Fase | Usuario interno | Frontstage | Backstage | Evidencia |
|---|---|---|---|---|
| Necesidad de viático | Identifica viaje o gasto | Orientación sobre requisitos | Verificación de políticas y tipos de viático | Política, instructivo o correo |
| Preparar solicitud | Reúne fecha, destino, monto y respaldo | Resolución de dudas y validación documental | Revisión de datos mínimos | Formulario y adjuntos |
| Enviar solicitud | Completa y remite el trámite | Confirmación de recepción | Registro del caso y seguimiento | Confirmación y ticket |
| Revisión y aprobación | Espera respuesta o correcciones | Evaluación, aprobación o rechazo | Validación de presupuesto, coherencia y firmas | Estado y observaciones |
| Cierre | Recibe aprobación o ajuste final | Comunicación de resolución | Archivo e historial actualizado | Comprobante e historial |

## Momentos de verdad

- El usuario no sabe si la solicitud quedó enviada correctamente.
- El usuario recibe una observación por monto o respaldo incorrecto.
- El usuario necesita revisar el estado del trámite sin enviar correos.

## Ideación y priorización

Se generaron 12 ideas para mejorar el flujo, entre ellas formulario único, validación en tiempo real, carga guiada de comprobantes, estado visible, checklist, historial y filtros de aprobación.

Las iniciativas priorizadas por alto impacto y bajo esfuerzo fueron:

- Formulario único.
- Validación en tiempo real.
- Estado del trámite visible.
- Botón de envío con checklist.

También se priorizaron como alto impacto y esfuerzo medio la carga guiada de comprobantes, la aprobación con filtros y el guardado automático.

## Prototipo

La solución propone dos flujos principales:

### Solicitud de viático

- Fecha de viaje, destino y monto estimado como campos obligatorios.
- Adjuntar respaldo requerido.
- Checklist previo al envío.
- Validación en tiempo real.
- Confirmación visible, ticket y estado inicial “En revisión”.

### Panel de aprobación

- Lista de solicitudes con solicitante, destino, fecha, monto y estado.
- Filtros para revisar solicitudes pendientes, observadas o aprobadas.
- Opciones para aprobar o solicitar corrección.
- Detalle del trámite e historial resumido.

## Pruebas de usabilidad

Se realizaron tareas de completar solicitudes, adjuntar respaldos y revisar o aprobar trámites con tres usuarios ficticios: Carla Muñoz, Diego Rojas y Paula Pérez.

| Hallazgo | Prioridad | Mejora aplicada |
|---|---|---|
| Dudas sobre campos obligatorios y montos | Alta | Etiquetas obligatorias, checklist y validación previa |
| Incertidumbre sobre el envío | Alta | Confirmación visible, ticket y estado inicial |
| Estado poco visible | Alta | Estado del trámite en la pantalla principal |
| Botón de adjuntar poco evidente | Media | Mayor visibilidad de carga guiada |
| Filtros del panel poco claros | Media | Filtros de aprobación más explícitos |

Los puntajes SUS registrados fueron 72, 68 y 75, lo que permitió identificar oportunidades concretas de mejora durante la iteración.

## Resultados esperados

- Menos errores de carga y menos solicitudes observadas.
- Mayor confianza al enviar un trámite.
- Mayor transparencia sobre el estado de cada solicitud.
- Menos consultas manuales por correo.
- Flujo de aprobación más ágil para Finanzas y responsables.

## Mi aporte como Product Owner

- Mapeé el servicio completo con un Service Blueprint.
- Identifiqué usuarios, necesidades, dolores y momentos de verdad.
- Sinteticé hallazgos en un insight, POV y preguntas How Might We.
- Generé y prioricé alternativas mediante brainstorming y matriz impacto-esfuerzo.
- Definí un prototipo de solicitud y aprobación de viáticos.
- Analicé pruebas de usabilidad y transformé los hallazgos en mejoras de producto.

## Aprendizajes

El proyecto mostró que una experiencia de servicio no depende solo de una interfaz. Es necesario comprender el recorrido completo del usuario, los procesos visibles y de soporte, y usar evidencia de pruebas para iterar. La validación, la confirmación y la trazabilidad fueron los elementos más importantes para reducir incertidumbre y errores.

# Agile Delivery Suite — Módulo 5

## Resumen

Agile Delivery Suite es una propuesta de plataforma interna para centralizar solicitudes, funcionalidades, incidencias y mejoras del área de innovación de Tech4You. El caso combina Scrum para el desarrollo y Kanban para soporte, utilizando Jira como herramienta central para visualizar, priorizar y medir el trabajo.

## Problema

La Dirección de Innovacin de Tech4You necesita mejorar la visibilidad del trabajo, reducir retrasos y coordinar mejor las tareas del equipo. El proceso actual dispersa solicitudes, funcionalidades pequeñas e incidencias, lo que genera poca claridad sobre prioridades, avances y bloqueos.

## Solución

Se propone un flujo ágil integrado que use:

- **Scrum** para el desarrollo de funcionalidades nuevas, con Sprints de dos semanas, roles claros y eventos regulares.
- **Kanban** para soporte, incidencias y pequeñas solicitudes, con tablero visible, límites WIP y mtricas de flujo.
- **Jira** como plataforma central para gestionar proyectos Scrum y Kanban, configurar tableros, automatizaciones y dashboards.

## Metodologías ágiles

### Los 4 valores del Manifiesto Ágil

1. Individuos e interacciones sobre procesos y herramientas.
2. Software funcionando sobre documentación extensiva.
3. Colaboración con el cliente sobre negociación contractual.
4. Respuesta ante el cambio sobre seguir un plan.

### Los 12 principios del Manifiesto Ágil

1. Satisfacer al cliente mediante entregas tempranas y continuas.
2. Aceptar cambios en los requisitos, incluso tarde en el desarrollo.
3. Entregar software funcionando con frecuencia.
4. Trabajar en conjunto con negocio y desarrollo a diario.
5. Construir proyectos alrededor de personas motivadas.
6. Favorecer la comunicación cara a cara.
7. El software funcionando es la principal medida de progreso.
8. Mantener un ritmo sostenible.
9. Atender a la excelencia técnica y el buen diseño.
10. Simplicidad: maximizar el trabajo no realizado.
11. Las mejores soluciones surgen de equipos autoorganizados.
12. Reflexionar regularmente para mejorar la forma de trabajo.

### Agile vs. Cascada

| Dimensión | Ágil | Cascada |
|---|---|---|
| Planificación | Iterativa y adaptable | Extensa y fija al inicio |
| Entregas | Incrementales y frecuentes | Una sola entrega al final |
| Cambios | Bienvenidos y esperados | Costosos y tardos |
| Cliente | Participa de forma continua | Participa solo al inicio y al final |
| Documentación | Ligera y útil | Exhaustiva y contractual |
| Medición del éxito | Valor entregado y satisfacción | Cumplimiento del plan y presupuesto |

### Riesgos que mitiga Ágil

- Reduce el riesgo de construir algo que no responda a la necesidad real del usuario, porque permite validar temprano.
- Disminuye el riesgo de detectar errores demasiado tarde, gracias a entregas frecuentes, inspección y adaptación.

## Kanban

Kanban se usa para gestionar soporte, incidencias y pequeñas solicitudes del área de innovación.

### Tablero Kanban propuesto

| Pendiente | En progreso | Revisión | Hecho |
|---|---|---|---|
| Solicitud nueva | Desarrollo activo | Validación / QA | Entregado |
| Prioridad definida | Trabajo en curso | Aprobación técnica | Completado |

### Límites WIP

- **Pendiente:** sin límite, porque solo refleja entrada de trabajo.
- **En progreso:** máximo 2 tarjetas, para evitar multitarea y acumulación.
- **Revisión:** máximo 1 tarjeta, porque suele ser un cuello de botella.
- **Hecho:** sin lmite.

### Justificacin de los lmites

Los lmites WIP ayudan a mejorar el foco, reducir el multitasking y hacer visibles los bloqueos. Cuando una columna se llena, el equipo se ve obligado a terminar antes de empezar más trabajo, lo que mejora el flujo y reduce el lead time.

### Métricas Kanban

| Tarjeta | Lead Time | Cycle Time |
|---|---|---|
| T1 | 4 das | 3 das |
| T2 | 5 das | 4 das |
| T3 | 3 das | 2 das |
| T4 | 6 das | 5 das |
| T5 | 4 das | 3 das |

### Cuello de botella y mejora

Si la columna **Revisin** acumula tarjetas, el cuello de botella está en la validacin. La mejora propuesta es limitar aún más el WIP en esa etapa, revisar el flujo de aprobacin y hacer pruebas más tempranas para evitar que el trabajo se detenga al final.

## Scrum

Scrum se usa para el desarrollo de la funcionalidad principal de Agile Delivery Suite, organizada en Sprints de dos semanas.

### Roles del equipo

- **Product Owner:** prioriza el backlog y maximiza el valor del producto.
- **Scrum Master:** facilita el proceso y elimina impedimentos.
- **Development Team:** construye incrementos "Done" con calidad tcnica.

### Product Backlog priorizado

| Prioridad | PBI | Historia de usuario | Estimacin |
|---|---|---|---|
| 1 | PBI-01 | Como usuario, quiero crear una nueva solicitud para registrar necesidades, incidencias o mejoras de forma ordenada. | 5 SP |
| 2 | PBI-02 | Como usuario, quiero consultar el estado de mis solicitudes para conocer su avance y detectar posibles bloqueos. | 5 SP |
| 3 | PBI-03 | Como usuario, quiero asignar prioridad a una solicitud para orientar la planificacin y facilitar la toma de decisiones. | 3 SP |
| 4 | PBI-04 | Como usuario, quiero adjuntar archivos a una solicitud para aportar antecedentes y evidencias relevantes. | 3 SP |
| 5 | PBI-05 | Como usuario, quiero comentar una solicitud para agregar informacin, resolver dudas y mantener trazabilidad de la conversacin. | 2 SP |
| 6 | PBI-06 | Como usuario, quiero filtrar solicitudes por estado para encontrar rápidamente las que están pendientes, en progreso o finalizadas. | 3 SP |
| 7 | PBI-07 | Como usuario, quiero recibir notificaciones de cambios para mantenerme informado sobre avances, actualizaciones y cierres. | 3 SP |
| 8 | PBI-08 | Como usuario, quiero cerrar una solicitud completada para confirmar su finalización y mantener actualizado el flujo de trabajo. | 2 SP |
| 9 | PBI-09 | Como usuario, quiero ver un resumen de métricas para evaluar el desempeño del flujo y apoyar la mejora continua. | 5 SP |
| 10 | PBI-10 | Como usuario, quiero exportar solicitudes a CSV para analizar la información fuera de la plataforma y compartir reportes. | 3 SP |

### Meta del Sprint

Entregar un flujo funcional mnimo para crear, consultar y actualizar solicitudes dentro de Agile Delivery Suite, permitiendo una demo usable al final del Sprint.

### Sprint Backlog

Para el Sprint de dos semanas, se seleccionan estos elementos:

- PBI-01.
- PBI-02.
- PBI-03.
- PBI-04.
- PBI-05.

**Total estimado:** 18 SP.

### Eventos del Sprint

- **Sprint Planning:** definir qué se hará y cómo se hará.
- **Daily Scrum:** revisar avances, bloqueos y plan para 24 horas.
- **Sprint Review:** mostrar el incremento a los interesados.
- **Sprint Retrospective:** identificar mejoras del proceso.

### Velocity al cierre

Si el Sprint planificó 18 SP y se completaron 15 SP, la velocity sera **15 SP**. Si el equipo normalmente entrega entre 15 y 18 SP, esta variabilidad puede deberse a historias más complejas o bloqueos no previstos.

## Jira

Jira se usa como plataforma central para gestionar el trabajo, visualizando proyectos Scrum y Kanban, configurando tableros, flujos y automatizaciones.

### Proyecto Scrum

Se crea un proyecto Scrum para el desarrollo de funcionalidades nuevas. Allí se usa:

- Backlog.
- Active Sprints.
- Burndown.
- Velocity.

### Proyecto Kanban

Se crea un proyecto Kanban para soporte y tareas continuas. Allí se usa:

- Columnas To Do / In Progress / Done.
- WIP limits.
- Control Chart.
- Lead Time y Cycle Time.

### Automatización básica

Regla propuesta:

- Cuando se cree una rama en Bitbucket, mover automáticamente el issue a **In Progress**.
- Cuando se fusione un pull request, mover el issue a **Done**.

Esta automatización reduce errores manuales y mantiene actualizado el estado real del trabajo.

### Dashboard para stakeholders

El dashboard puede incluir:

- Sprint Health.
- Burndown Chart.
- Control Chart.
- Pie Chart por tipo de issue.
- Issues asignados al usuario.

## Métricas

Las métricas ayudan a inspeccionar el desempeño y a tomar decisiones basadas en datos.

### Velocity

Permite estimar la capacidad del equipo por Sprint, aunque no debe usarse como promesa exacta porque vara según complejidad y bloqueos.

### Burndown

Muestra el trabajo pendiente versus el tiempo y ayuda a detectar caídas tardías o scope creep.

### Lead Time y Cycle Time

- **Lead Time:** desde que se solicita hasta que se entrega.
- **Cycle Time:** desde que se empieza a trabajar hasta que termina.

### CFD

El Cumulative Flow Diagram permite detectar acumulación de trabajo y cuellos de botella, especialmente cuando la banda de "In Progress" se ensancha.

## Definition of Done y políticas WIP

### Definition of Done

Una historia se considera terminada solo si:

- El código fue revisado.
- Pasó las pruebas.
- Tiene documentación mínima.
- Cumple criterios de aceptación.
- Está lista para desplegarse.

### Política WIP

- Limitar **En progreso** a 2 tarjetas.
- Limitar **Revisión** a 1 tarjeta.
- No iniciar trabajo nuevo si hay bloqueos visibles.

## Mi aporte como Product Owner

- Definí un flujo ágil integrado que combina Scrum y Kanban según el tipo de trabajo.
- Prioricé un Product Backlog con historias de usuario claras y estimadas en Story Points.
- Definí una meta de Sprint y seleccioné un Sprint Backlog realista.
- Establecí Definition of Done y políticas WIP para mejorar calidad y flujo.
- Diseñé un tablero Kanban con límites WIP y métricas de flujo.
- Propuse automatizaciones y un dashboard en Jira para visibilidad y trazabilidad.
- Usé métricas (Velocity, Burndown, Lead Time, Cycle Time, CFD) para inspeccionar y adaptar.

## Aprendizajes

Este proyecto demostró que Scrum y Kanban no se excluyen, sino que se complementan. Scrum sirve para organizar el desarrollo en ciclos cortos con objetivos claros, mientras Kanban ayuda a sostener el flujo continuo y controlar los bloqueos.

También aprendí que Jira permite traducir la teoría ágil en un sistema visible y medible, con tableros, automatizaciones y métricas útiles para la gestión diaria. La clave no está solo en usar herramientas, sino en sostener una cultura de transparencia, inspección y adaptación.

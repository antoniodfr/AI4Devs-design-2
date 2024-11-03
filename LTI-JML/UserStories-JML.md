
# User Stories Detalladas

## 1. Creación de Puestos de Trabajo  
**Formato estándar:**  
**Como** reclutador de LTI, **quiero** crear nuevas vacantes de empleo en el sistema **para** definir los roles y responsabilidades del puesto y atraer a los candidatos adecuados.

**Descripción:**  
El reclutador necesita una interfaz en el sistema ATS para crear y definir puestos de trabajo, incluyendo la descripción del rol, los requisitos y las responsabilidades principales.

**Criterios de Aceptación:**  
- **Dado que** soy un reclutador en la interfaz de creación de vacantes, **cuando** ingreso la información del puesto (nombre, descripción, requisitos, etc.), **entonces** puedo guardar el puesto de trabajo en el sistema.
- **Dado que** completé la creación del puesto, **cuando** guarde los datos, **entonces** el puesto estará visible en la lista de vacantes internas.

**Notas adicionales:**  
Este proceso debe permitir la reutilización de descripciones de puestos similares para agilizar la creación de nuevas vacantes.

**Tareas:**  
- Crear formulario de ingreso de datos para la vacante.
- Incluir campos de descripción, requisitos y responsabilidades.
- Implementar opción de guardar y confirmar la creación del puesto.
- Realizar pruebas de usabilidad del formulario.

---

## 2. Publicación de Vacantes en Múltiples Plataformas  
**Formato estándar:**  
**Como** reclutador de LTI, **quiero** publicar automáticamente las vacantes en varias plataformas de empleo desde el sistema **para** maximizar el alcance y recibir aplicaciones de candidatos de diferentes fuentes.

**Descripción:**  
El sistema debe permitir la publicación de vacantes en varias plataformas de empleo (por ejemplo, LinkedIn, Indeed) con un solo clic para agilizar el proceso.

**Criterios de Aceptación:**  
- **Dado que** se ha creado una vacante, **cuando** selecciono la opción de “Publicar en múltiples plataformas”, **entonces** el sistema muestra las plataformas disponibles.
- **Dado que** selecciono las plataformas deseadas, **cuando** confirmo la publicación, **entonces** la vacante se publica automáticamente en todas las plataformas seleccionadas.

**Notas adicionales:**  
Las integraciones de API de cada plataforma deben ser revisadas periódicamente para garantizar la conexión y el buen funcionamiento.

**Tareas:**  
- Integrar el sistema ATS con las API de las principales plataformas de empleo.
- Crear interfaz de selección de plataformas de publicación.
- Probar el flujo de publicación y confirmar en cada plataforma.

---

## 3. Revisión y Filtrado de Candidaturas  
**Formato estándar:**  
**Como** reclutador de LTI, **quiero** revisar y filtrar las solicitudes de candidatos en función de criterios predefinidos **para** identificar rápidamente a los candidatos que cumplen con los requisitos básicos del puesto.

**Descripción:**  
El sistema debe ofrecer una función de filtrado que permita al reclutador definir y aplicar filtros a las candidaturas recibidas, como experiencia, educación, habilidades, etc.

**Criterios de Aceptación:**  
- **Dado que** estoy en la lista de candidaturas de una vacante, **cuando** aplico un filtro por experiencia o habilidades, **entonces** el sistema muestra solo los candidatos que cumplen con estos criterios.
- **Dado que** he aplicado un filtro, **cuando** elimino el filtro, **entonces** el sistema vuelve a mostrar todas las candidaturas.

**Notas adicionales:**  
Los filtros deben poder ser guardados como “criterios de filtrado” para aplicarse a vacantes similares en el futuro.

**Tareas:**  
- Diseñar la interfaz de filtros con opciones de experiencia, educación, y habilidades.
- Implementar el motor de filtrado en la lista de candidatos.
- Pruebas de usabilidad para la interfaz de filtrado.

---

## 4. Administración de Pruebas en Línea  
**Formato estándar:**  
**Como** reclutador de LTI, **quiero** asignar y administrar pruebas en línea a los candidatos seleccionados **para** evaluar sus habilidades técnicas y aptitudes antes de la entrevista.

**Descripción:**  
El sistema debe permitir asignar pruebas técnicas o de aptitudes a los candidatos seleccionados y gestionar sus resultados.

**Criterios de Aceptación:**  
- **Dado que** selecciono un candidato en la lista, **cuando** le asigno una prueba en línea, **entonces** el candidato recibe un enlace para completar la prueba.
- **Dado que** el candidato ha completado la prueba, **cuando** reviso su perfil, **entonces** puedo ver los resultados y puntajes obtenidos.

**Notas adicionales:**  
Debe incluirse una opción de notificación automática al candidato con las instrucciones de la prueba.

**Tareas:**  
- Integrar sistema de pruebas con plataforma de evaluaciones.
- Crear interfaz de asignación de pruebas en el perfil del candidato.
- Implementar vista de resultados en el perfil del candidato.

---

## 5. Aplicación a Vacantes en Línea  
**Formato estándar:**  
**Como** candidato, **quiero** postularme a una vacante en línea **para** enviar mi solicitud de empleo de forma rápida y conveniente.

**Descripción:**  
El candidato necesita una interfaz que le permita buscar vacantes, revisar la descripción y requisitos, y enviar su solicitud con facilidad.

**Criterios de Aceptación:**  
- **Dado que** soy un candidato en la página de una vacante, **cuando** hago clic en "Aplicar", **entonces** se me solicita adjuntar mi CV y completar la información requerida.
- **Dado que** envío mi solicitud, **cuando** se complete el proceso, **entonces** recibo una confirmación de que mi aplicación ha sido enviada exitosamente.

**Notas adicionales:**  
Debe incluirse una opción de confirmación automática por correo electrónico con detalles de la vacante aplicada.

**Tareas:**  
- Crear formulario de aplicación con campos de información del candidato.
- Habilitar carga de CV y otros documentos requeridos.
- Implementar notificación de confirmación por correo.

---

---

## Backlog de Producto

| User Story                                           | Impacto en el Usuario y Valor del Negocio | Urgencia (Mercado y Feedback) | Complejidad y Esfuerzo | Riesgos y Dependencias            |
|------------------------------------------------------|------------------------------------------|-------------------------------|------------------------|------------------------------------|
| Creación de Puestos de Trabajo                       | Alto: Central para el proceso            | Alta: Fundamental para iniciar | Media                  | Dependiente de interfaz principal |
| Publicación en Múltiples Plataformas                 | Alto: Aumenta visibilidad de vacantes    | Media: Basado en competencia   | Alta                   | API de plataformas externas       |
| Revisión y Filtrado de Candidaturas                  | Muy Alto: Mejora la eficiencia           | Alta: Feedback de usuarios     | Alta                   | Ninguna importante                |
| Administración de Pruebas en Línea                   | Muy Alto: Filtra candidatos aptos        | Alta: Demanda del reclutador   | Media                  | Integración con plataforma de pruebas |
| Aplicación a Vacantes en Línea                       | Alto: Mejora experiencia del candidato   | Muy Alta: Crítica en el flujo  | Baja                   | Ninguna importante                |
| Seguimiento de Estado de Aplicación                  | Alto: Transparencia para candidatos      | Media: Requiere mejoras en UX  | Media                  | Depende del flujo de aplicación   |
| Confirmación y Preparación de Entrevistas            | Alto: Aumenta compromiso del candidato   | Media: Feedback de candidatos  | Media                  | Integración con sistema de notificaciones |
| Reportes de Progreso de Contratación                 | Muy Alto: Visibilidad para managers      | Alta: Mejora toma de decisiones | Alta                   | Depende de datos de otras funciones |
| Aprobar o Rechazar Ofertas de Contratación           | Alto: Control de calidad en ofertas      | Media: Basado en políticas     | Media                  | Ninguna importante                |
| Métricas de Fuente de Candidatos                     | Medio: Optimización de reclutamiento     | Media: Para futuras estrategias | Media                  | Depende de integración con fuentes de datos |

---

### Backlog de Producto con Técnicas de Priorización

| User Story                                           | Impacto en el Usuario y Valor del Negocio | Urgencia (Mercado y Feedback) | Complejidad y Esfuerzo | Riesgos y Dependencias            | Técnicas de Priorización Aplicadas |
|------------------------------------------------------|------------------------------------------|-------------------------------|------------------------|------------------------------------|------------------------------------|
| Creación de Puestos de Trabajo                       | Alto: Central para el proceso            | Alta: Fundamental para iniciar | Media                  | Dependiente de interfaz principal | MoSCoW: Must have, ICE: 21.6, RICE: 162 |
| Publicación en Múltiples Plataformas                 | Alto: Aumenta visibilidad de vacantes    | Media: Basado en competencia   | Alta                   | API de plataformas externas       | MoSCoW: Should have, ICE: 19.6, RICE: 105 |
| Revisión y Filtrado de Candidaturas                  | Muy Alto: Mejora la eficiencia           | Alta: Feedback de usuarios     | Alta                   | Ninguna importante                | MoSCoW: Must have, ICE: 21.6, RICE: 129 |
| Administración de Pruebas en Línea                   | Muy Alto: Filtra candidatos aptos        | Alta: Demanda del reclutador   | Media                  | Integración con plataforma de pruebas | MoSCoW: Must have, ICE: 20.8, RICE: 128 |
| Aplicación a Vacantes en Línea                       | Alto: Mejora experiencia del candidato   | Muy Alta: Crítica en el flujo  | Baja                   | Ninguna importante                | MoSCoW: Must have, ICE: 24.3, RICE: 270 |
| Seguimiento de Estado de Aplicación                  | Alto: Transparencia para candidatos      | Media: Requiere mejoras en UX  | Media                  | Depende del flujo de aplicación   | MoSCoW: Should have, ICE: 20.4, RICE: 112 |
| Confirmación y Preparación de Entrevistas            | Alto: Aumenta compromiso del candidato   | Media: Feedback de candidatos  | Media                  | Integración con sistema de notificaciones | MoSCoW: Should have, ICE: 20.0, RICE: 84 |
| Reportes de Progreso de Contratación                 | Muy Alto: Visibilidad para managers      | Alta: Mejora toma de decisiones | Alta                   | Depende de datos de otras funciones | MoSCoW: Must have, ICE: 20.8, RICE: 96 |
| Aprobar o Rechazar Ofertas de Contratación           | Alto: Control de calidad en ofertas      | Media: Basado en políticas     | Media                  | Ninguna importante                | MoSCoW: Should have, ICE: 18.4, RICE: 84 |
| Métricas de Fuente de Candidatos                     | Medio: Optimización de reclutamiento     | Media: Para futuras estrategias | Media                  | Depende de integración con fuentes de datos | MoSCoW: Could have, ICE: 17.4, RICE: 42 |

---

## Tickets de Trabajo para "Revisión y Filtrado de Candidaturas"

### Ticket: ATS-1001

**Título:** Creación de Interfaz de Filtros para Revisión de Candidaturas

**Descripción:**  
Desarrollar la interfaz de usuario que permitirá a los reclutadores aplicar filtros para la revisión de candidaturas. La interfaz debe incluir opciones de filtrado por experiencia, educación, habilidades y ubicación, con un diseño intuitivo y claro.

**Criterios de Aceptación:**  
- La interfaz muestra opciones de filtros desplegables para cada criterio.
- El usuario puede seleccionar múltiples criterios en cada categoría.
- Los filtros aplicados se muestran visualmente en la parte superior de la lista de resultados.

**Prioridad:** Alta

**Estimación de Esfuerzo:** 2 días

**Asignación:** Equipo de Frontend

**Etiquetas:** `frontend`, `UI`, `filtros`, `candidatos`

**Comentarios y Notas:**  
Diseño debe alinearse con la guía de estilos del sistema ATS y ser adaptable a dispositivos móviles.

**Enlaces o Referencias:**  
Prototipo de diseño en Figma.

**Historial de Cambios:**  
- 03/11/2024: Ticket creado.

---

### Ticket: ATS-1002

**Título:** Implementación de Filtros en Backend

**Descripción:**  
Crear la lógica de backend para aplicar filtros en las solicitudes de candidatos. Esto incluye la configuración de consultas para filtrar por criterios seleccionados y optimización para grandes volúmenes de datos.

**Criterios de Aceptación:**  
- Los filtros seleccionados en la interfaz se traducen en consultas de base de datos.
- El backend devuelve solo los candidatos que cumplen con los criterios seleccionados.
- Tiempo de respuesta del filtrado no debe superar los 2 segundos para listas de hasta 10,000 candidatos.

**Prioridad:** Alta

**Estimación de Esfuerzo:** 4 días

**Asignación:** Equipo de Backend

**Etiquetas:** `backend`, `filtros`, `base de datos`

**Comentarios y Notas:**  
Revisar optimización de consultas en la base de datos para garantizar rendimiento.

**Enlaces o Referencias:**  
Documentación de estructura de base de datos.

**Historial de Cambios:**  
- 03/11/2024: Ticket creado.

---

### Ticket: ATS-1003

**Título:** Pruebas de Funcionalidad de Filtros de Candidaturas

**Descripción:**  
Desarrollar y ejecutar pruebas funcionales para asegurar que los filtros de candidaturas funcionan correctamente y cumplen con los criterios definidos. Incluir casos de pruebas para cada criterio de filtro.

**Criterios de Aceptación:**  
- Se prueban todos los criterios de filtro individualmente y en combinación.
- Los resultados de pruebas confirman que los filtros devuelven los candidatos correctos en cada caso.
- Se documentan los resultados de todas las pruebas en el sistema de seguimiento.

**Prioridad:** Media

**Estimación de Esfuerzo:** 2 días

**Asignación:** Equipo de QA

**Etiquetas:** `QA`, `testing`, `filtros`

**Comentarios y Notas:**  
Considerar pruebas de carga para verificar el rendimiento bajo diferentes volúmenes de datos.

**Enlaces o Referencias:**  
Casos de prueba en el sistema de gestión de QA.

**Historial de Cambios:**  
- 03/11/2024: Ticket creado.

---

### Ticket: ATS-1004

**Título:** Implementación de Cache para Mejorar Rendimiento de Filtros

**Descripción:**  
Configurar un sistema de cache que permita reducir el tiempo de respuesta de los filtros en búsquedas frecuentes o con resultados similares. La cache debe refrescarse periódicamente y no debe afectar los datos en tiempo real.

**Criterios de Aceptación:**  
- Las consultas filtradas frecuentes se recuperan de la cache.
- El tiempo de respuesta se reduce significativamente para búsquedas repetidas.
- La cache se actualiza cada 5 minutos y se invalida al actualizarse el perfil de un candidato.

**Prioridad:** Media

**Estimación de Esfuerzo:** 4 días

**Asignación:** Equipo de Backend

**Etiquetas:** `backend`, `optimización`, `rendimiento`, `cache`

**Comentarios y Notas:**  
Implementar una estrategia de invalidación de cache adecuada para no comprometer la frescura de los datos.

**Enlaces o Referencias:**  
Documentación técnica sobre caching en el sistema ATS.

**Historial de Cambios:**  
- 03/11/2024: Ticket creado.

---

### Ticket: ATS-1005

**Título:** Mejora de la Visualización de Filtros Aplicados

**Descripción:**  
Actualizar la interfaz para que los filtros aplicados se muestren de forma visual y destacada, permitiendo a los reclutadores identificar y eliminar filtros fácilmente desde la lista de resultados.

**Criterios de Aceptación:**  
- Cada filtro aplicado se muestra visualmente en la parte superior de la lista de resultados.
- El usuario puede eliminar filtros aplicados individualmente desde la visualización.
- La lista de resultados se actualiza en tiempo real al eliminar un filtro.

**Prioridad:** Media

**Estimación de Esfuerzo:** 1 día

**Asignación:** Equipo de Frontend

**Etiquetas:** `frontend`, `UX`, `filtros`, `interfaz`

**Comentarios y Notas:**  
La visualización de filtros aplicados debe ser clara y no ocupar mucho espacio en la pantalla.

**Enlaces o Referencias:**  
Prototipo de UX con filtros aplicados.

**Historial de Cambios:**  
- 03/11/2024: Ticket creado.

---

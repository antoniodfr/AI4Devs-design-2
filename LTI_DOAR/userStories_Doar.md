IMPLEMENTACION LTI

1. User Story: Organización de Candidatos con Etiquetas
Formato estándar: Como reclutador, quiero asignar etiquetas personalizadas a los candidatos para organizar mejor la base de datos y facilitar futuras búsquedas.

Descripción: Permitir que el reclutador etiquete a los candidatos con términos específicos que reflejen sus cualidades o nivel en el proceso de selección.

Criterios de Aceptación:

Dado que el reclutador tiene acceso a la base de datos de candidatos, cuando selecciona un perfil, entonces debe poder añadir una etiqueta personalizada.
Dado que se ha añadido una etiqueta a un candidato, cuando el reclutador busca por esa etiqueta en la base de datos, entonces el candidato debe aparecer en los resultados.
Notas adicionales: Las etiquetas deben ser visibles en el perfil de cada candidato y en las listas de búsqueda para facilitar la organización.

Tareas:

Diseñar interfaz de usuario para añadir etiquetas.
Implementar funcionalidad de filtrado por etiquetas en la base de datos.
Validar que las etiquetas sean visibles y modificables en el perfil de cada candidato.

2. User Story: Resumen Semanal del Proceso de Selección
Formato estándar: Como manager, quiero recibir un resumen semanal del estado de cada vacante en mi equipo para estar informado del progreso sin tener que solicitar actualizaciones.

Descripción: El sistema debe enviar automáticamente al manager un resumen que incluya el número de candidatos en cada fase del proceso de selección.

Criterios de Aceptación:

Dado que ha pasado una semana, cuando el sistema genera el reporte, entonces debe enviarse un resumen por email al manager.
Dado que se han actualizado los candidatos en el proceso, cuando el manager recibe el resumen, entonces debe ver el estado actualizado de cada vacante.
Notas adicionales: El resumen debe ser claro y directo, con un formato estándar que incluya las métricas clave.

Tareas:

Crear una plantilla de resumen semanal.
Implementar un cron job para generar y enviar el resumen cada semana.
Configurar los permisos para que los managers solo reciban información de las vacantes de su equipo.
3. User Story: Actualización del Perfil de Candidato
Formato estándar: Como candidato, quiero actualizar mi perfil en el sistema para reflejar nuevas experiencias o habilidades y mejorar mis oportunidades de selección.

Descripción: El sistema debe permitir que los candidatos puedan modificar sus perfiles y añadir nuevas experiencias o habilidades después de haber enviado su solicitud.

Criterios de Aceptación:

Dado que el candidato tiene acceso al sistema, cuando inicia sesión, entonces debe poder editar su perfil.
Dado que el perfil ha sido actualizado, cuando el reclutador revisa el perfil, entonces debe ver la información nueva o modificada.
Notas adicionales: Las modificaciones en el perfil deben notificarse al reclutador para que esté al tanto de las actualizaciones relevantes.

Tareas:

Crear interfaz de edición de perfil para candidatos.
Programar notificación automática al reclutador cuando se realiza una actualización de perfil.
Implementar validación de datos para asegurar coherencia en las actualizaciones.
4. User Story: Generación de Reportes de Rendimiento de Vacantes
Formato estándar: Como reclutador, quiero generar reportes de rendimiento de cada vacante para identificar áreas de mejora en el proceso de selección.

Descripción: El sistema debe permitir al reclutador generar reportes que detallen el tiempo en cada fase y la tasa de rechazo de candidatos.

Criterios de Aceptación:

Dado que el reclutador desea revisar el rendimiento, cuando selecciona una vacante y solicita un reporte, entonces el sistema debe generar un documento con las métricas específicas.
Dado que el reporte se ha generado, cuando el reclutador revisa los datos, entonces debe poder identificar las fases con mayor tiempo o tasa de rechazo.
Notas adicionales: El reporte debe ser exportable a PDF o Excel para permitir su análisis fuera del sistema.

Tareas:

Crear módulo de generación de reportes para cada vacante.
Incluir métricas clave en el reporte (tiempo en fases, tasa de rechazo).
Implementar opciones de exportación en PDF y Excel.
5. User Story: Comentarios y Feedback en Tiempo Real
Formato estándar: Como manager y reclutador, quiero poder comentar en el perfil de los candidatos para coordinar el feedback de manera centralizada y en tiempo real.

Descripción: El sistema debe habilitar un espacio de comentarios en cada perfil de candidato, donde tanto managers como reclutadores puedan dejar observaciones o feedback.

Criterios de Aceptación:

Dado que un manager o reclutador está revisando un perfil, cuando añade un comentario, entonces el otro usuario debe poder verlo en tiempo real.
Dado que se ha añadido un comentario, cuando un usuario abre el perfil, entonces debe ver la última conversación y responder si es necesario.
Notas adicionales: Los comentarios deben estar organizados cronológicamente y ser visibles solo para el equipo de selección.

Tareas:

Crear interfaz de comentarios en el perfil de cada candidato.
Configurar actualización en tiempo real para sincronizar los comentarios.
Establecer permisos para que solo managers y reclutadores puedan acceder a los comentarios.

User Story: Interfaz Compleja y Difícil de Navegar

Formato estándar: Como reclutador, quiero una interfaz más sencilla y con accesos rápidos a las funciones esenciales para poder gestionar mis tareas de reclutamiento de manera más eficiente.
Descripción: Simplificar la interfaz para que los reclutadores encuentren y accedan rápidamente a las funciones esenciales, mejorando la experiencia de usuario y reduciendo el tiempo necesario para completar acciones.
Criterios de Aceptación:
Dado que el reclutador está utilizando el ATS, cuando accede a la plataforma, entonces debe ver un menú simplificado con accesos rápidos a las funciones más usadas.
Dado que el reclutador necesita realizar tareas frecuentes, cuando selecciona una opción en el menú rápido, entonces debe ser dirigido a la funcionalidad correspondiente de manera inmediata.
Notas adicionales: Priorizar la disposición de accesos a funciones más utilizadas, basados en análisis de uso.
Tareas:
Rediseñar la interfaz para incluir accesos rápidos.
Implementar el menú simplificado en la plataforma.
Realizar pruebas de usabilidad para confirmar la mejora.

User Story: Filtro de Candidatos Poco Preciso

Formato estándar: Como reclutador, quiero disponer de un sistema de filtrado avanzado que permita búsquedas por palabras clave, para poder encontrar candidatos con habilidades específicas de manera más eficiente.
Descripción: Mejorar la funcionalidad de filtrado para que los reclutadores puedan realizar búsquedas avanzadas y específicas que identifiquen rápidamente a los candidatos con las habilidades más relevantes para la vacante.
Criterios de Aceptación:
Dado que el reclutador necesita encontrar candidatos específicos, cuando utiliza el sistema de filtrado, entonces debe poder realizar búsquedas por palabras clave, booleanas y con filtros avanzados.
Dado que el reclutador ha aplicado filtros avanzados, cuando ve los resultados, entonces solo deben aparecer los candidatos que cumplen con los criterios establecidos.
Notas adicionales: Incluir opciones como “Y/O” y búsquedas específicas por competencias técnicas.
Tareas:
Desarrollar e implementar el sistema de búsqueda avanzada.
Configurar opciones de filtro booleanas y por palabra clave.
Realizar pruebas de funcionalidad y precisión de los filtros.

User Story: Integración Limitada con Herramientas de Comunicación Externa

Formato estándar: Como manager, quiero que el ATS se integre con herramientas de comunicación como Microsoft Teams, para facilitar la coordinación y el feedback en tiempo real con el equipo de reclutamiento.
Descripción: Aumentar las opciones de integración del ATS con herramientas de comunicación de uso frecuente para mejorar la colaboración entre los equipos y agilizar la toma de decisiones.
Criterios de Aceptación:
Dado que el ATS está integrado con Microsoft Teams, cuando el manager o reclutador deja un comentario en un perfil, entonces el equipo debe recibir una notificación en tiempo real.
Dado que el equipo está usando Microsoft Teams, cuando se comparte un enlace del ATS en un chat, entonces debe redirigir correctamente a la información específica en la plataforma.
Notas adicionales: Facilitar la configuración de notificaciones personalizadas para evitar exceso de notificaciones.
Tareas:
Configurar la integración con Microsoft Teams y habilitar las notificaciones en tiempo real.
Desarrollar funcionalidad para compartir perfiles y comentarios del ATS en Microsoft Teams.
Realizar pruebas de usabilidad e integraciones.

User Story: Falta de Reportes Automatizados para el Seguimiento de Candidatos

Formato estándar: Como manager, quiero recibir reportes semanales automatizados sobre el estado de los candidatos para estar al tanto del progreso sin tener que consultar manualmente el sistema.
Descripción: Automatizar el envío de reportes para que los managers reciban actualizaciones del estado de los candidatos y del progreso de las vacantes sin tener que entrar al sistema.
Criterios de Aceptación:
Dado que ha pasado una semana, cuando el sistema genera el reporte, entonces el manager debe recibirlo por email con un resumen del progreso de las vacantes.
Dado que se envían reportes semanales, cuando el manager revisa el email, entonces debe ver el estado actualizado de cada candidato y el progreso en cada vacante.
Notas adicionales: Considerar la opción de incluir un resumen visual (gráficos de progreso) en el reporte para facilitar la revisión.
Tareas:
Desarrollar el módulo de reportes automatizados.
Implementar cron jobs para generar y enviar reportes semanalmente.
Configurar contenido visual en los reportes (tablas, gráficos).

User Story: Falta de Notificaciones de Estado para los Candidatos

Formato estándar: Como candidato, quiero recibir notificaciones automáticas sobre el estado de mi solicitud para saber si he avanzado en el proceso o no.
Descripción: Implementar notificaciones automáticas en el ATS para que los candidatos reciban actualizaciones sobre su estado, mejorando la transparencia y su experiencia durante el proceso de selección.
Criterios de Aceptación:
Dado que el estado de un candidato ha cambiado, cuando el sistema registra este cambio, entonces el candidato debe recibir una notificación (por email o en la plataforma) con la actualización de su estatus.
Dado que el candidato ha recibido una notificación, cuando inicia sesión en el sistema, entonces debe poder ver su estado actualizado en el perfil.
Notas adicionales: Las notificaciones deben ser claras y contener solo información relevante sobre el estado de la solicitud.
Tareas:
Implementar un sistema de notificaciones automáticas para cambios de estado.
Configurar las notificaciones para ser enviadas por email o en la plataforma.
Realizar pruebas para verificar la precisión y el timing de las notificaciones.

# Backlog de User Stories

| **Tema del Backlog**                                 | **Impacto en el Usuario y Valor del Negocio** | **Urgencia** | **Complejidad y Esfuerzo** | **Riesgos y Dependencias** |
|------------------------------------------------------|-----------------------------------------------|--------------|----------------------------|-----------------------------|
| Organización de Candidatos con Etiquetas             | Medio                                        | Bajo         | Bajo                       | Depende del sistema de almacenamiento de datos; riesgo de implementación de UI consistente |
| Resumen Semanal del Proceso de Selección             | Medio                                        | Medio        | Bajo                       | Sin dependencias importantes, bajo riesgo |
| Actualización del Perfil de Candidato                | Alto                                         | Medio        | Medio                      | Requiere interfaz de usuario amigable; riesgo de duplicación de datos |
| Generación de Reportes de Rendimiento de Vacantes    | Alto                                         | Alto         | Medio                      | Riesgo de carga adicional en la base de datos; depende de métricas disponibles en el sistema |
| Comentarios y Feedback en Tiempo Real                | Alto                                         | Alto         | Alto                       | Depende de la sincronización de datos en tiempo real; posible retraso de actualización |
| Interfaz Compleja y Difícil de Navegar               | Alto                                         | Alto         | Medio                      | Depende del diseño UX; riesgo de necesitar cambios en el frontend |
| Filtro de Candidatos Poco Preciso                    | Alto                                         | Alto         | Alto                       | Riesgo de rendimiento en grandes volúmenes de datos; alta dependencia del backend de búsquedas |
| Integración Limitada con Herramientas de Comunicación Externa | Medio                  | Medio        | Alto                       | Riesgo de incompatibilidad con API externas; depende de sistemas externos (Teams) |
| Falta de Reportes Automatizados para el Seguimiento de Candidatos | Medio             | Medio        | Medio                      | Requiere configuración de cron jobs y validación del sistema de permisos |
| Falta de Notificaciones de Estado para los Candidatos | Alto                | Alto         | Medio                      | Depende del sistema de notificaciones; riesgo de saturación de notificaciones o duplicación |



# Plan de Implementación de Generación de Reportes

| **Tarea**                             | **Descripción**                                                                                                    | **Impacto en el Usuario y Valor del Negocio** | **Complejidad de Implementación** | **Dependencias y Riesgos**                                                        | **Esfuerzo (puntos)** |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|-----------------------------------|-----------------------------------------------------------------------------------|------------------------|
| Diseñar estructura de datos del reporte | Definir las métricas clave (por ejemplo, tiempo en cada fase, tasa de rechazo) y la estructura de datos del reporte. | Alto                                          | Medio                             | Riesgo de sobrecarga si los datos se extraen de múltiples fuentes de datos.        | 3                      |
| Desarrollar lógica de agregación de datos | Implementar lógica para consolidar los datos de vacantes y candidatos en un formato estructurado.                 | Alto                                          | Alto                              | Riesgo de inconsistencias si las fuentes de datos no están alineadas.              | 5                      |
| Implementar módulo de generación de reportes | Crear el módulo que organiza la agregación de datos y construye el reporte a partir de la estructura definida.    | Alto                                          | Alto                              | Depende de la disponibilidad de métricas en el sistema.                            | 5                      |
| Crear visualización de métricas clave  | Crear visualizaciones (gráficos, tablas) dentro del reporte para facilitar el análisis de datos por parte de los usuarios. | Alto                                | Medio                             | Requiere colaboración con el equipo de diseño para crear visualizaciones intuitivas. | 5                      |
| Implementar opción de exportación a PDF | Desarrollar la funcionalidad que permita al usuario exportar el reporte en formato PDF.                           | Medio                                         | Medio                             | Riesgo de compatibilidad con distintos lectores de PDF.                            | 3                      |
| Implementar opción de exportación a Excel | Desarrollar la funcionalidad que permita al usuario exportar el reporte en formato Excel.                        | Medio                                         | Medio                             | Riesgo de compatibilidad con versiones de Excel.                                   | 3                      |
| Configurar acceso basado en roles      | Asegurar que solo los usuarios con el rol adecuado puedan generar y visualizar reportes.                          | Alto                                          | Bajo                              | Riesgo de violaciones de permisos si no se configuran correctamente.               | 3                      |
| Pruebas de precisión en datos          | Realizar pruebas de precisión en los datos agregados para asegurar consistencia en los reportes.                  | Alto                                          | Medio                             | Riesgo de datos desactualizados en los reportes si las pruebas fallan.             | 3                      |
| Pruebas de consistencia de visualización | Verificar que las visualizaciones en los reportes reflejan correctamente los datos de vacantes.                  | Alto                                          | Medio                             | Riesgo de inconsistencias visuales si las pruebas fallan.                          | 3                      |
| Configurar cron job para actualizaciones | Configurar un cron job que actualice los reportes periódicamente para reflejar el rendimiento en tiempo real.    | Medio                                         | Medio                             | Dependencia de recursos del servidor; riesgo de fallos en las actualizaciones.     | 3                      |

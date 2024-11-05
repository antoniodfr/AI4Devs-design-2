# User Stories


### User Story 1

**ID:** HU001  
**Título de la Historia de Usuario:** Como Reclutador, quiero crear y publicar vacantes en múltiples plataformas, para que pueda atraer candidatos calificados y recibir sus aplicaciones en un solo lugar.

**Criterios de Aceptación:**  
- **Dado que** tengo una vacante disponible, **cuando** ingreso los detalles de la vacante (título, descripción, requisitos, ubicación), **entonces** debería poder guardarla en el sistema.
- **Dado que** deseo aumentar la visibilidad de una vacante, **cuando** selecciono las plataformas externas (ej. LinkedIn), **entonces** el sistema debería publicar automáticamente la vacante en esas plataformas.
- **Dado que** he guardado los detalles de la vacante, **cuando** la reviso, **entonces** debería poder previsualizarla antes de publicarla.

**Notas Adicionales:**  
Considerar integración con LinkedIn para la publicación externa.

**Historias de Usuario Relacionadas:**  
HU002 (Recepción de aplicaciones)

---

### User Story 2

**ID:** HU002  
**Título de la Historia de Usuario:** Como Reclutador, quiero recibir y almacenar todas las aplicaciones de candidatos en un solo lugar, para que pueda revisarlas de manera centralizada y eficiente.

**Criterios de Aceptación:**  
- **Dado que** la vacante está publicada, **cuando** un candidato aplica, **entonces** su solicitud debería ser almacenada en la plataforma junto con los detalles de la vacante.
- **Dado que** recibo aplicaciones, **cuando** reviso el listado de candidatos, **entonces** debería poder acceder a las aplicaciones desde un solo lugar dentro del sistema.

**Notas Adicionales:**  
El sistema debe enviar notificaciones al reclutador cuando se reciba una nueva aplicación.

**Historias de Usuario Relacionadas:**  
HU001 (Publicar Vacante), HU003 (Filtrado de candidatos)

---

### User Story 3

**ID:** HU003  
**Título de la Historia de Usuario:** Como Reclutador, quiero aplicar filtros iniciales a las aplicaciones recibidas, para que pueda identificar rápidamente a los candidatos que cumplen con los requisitos básicos de la vacante.

**Criterios de Aceptación:**  
- **Dado que** tengo una lista de candidatos, **cuando** configuro criterios específicos (como experiencia mínima, ubicación), **entonces** el sistema debería filtrar automáticamente los candidatos que no cumplan con estos criterios.
- **Dado que** deseo hacer una preselección, **cuando** aplico el filtro, **entonces** debería ver solo a los candidatos que cumplen con los requisitos.

**Notas Adicionales:**  
Incluir en el sistema filtros personalizables por vacante.

**Historias de Usuario Relacionadas:**  
HU002 (Recepción de Aplicaciones Centralizada), HU004 (Entrevista automatizada)

---

### User Story 4

**ID:** HU004  
**Título de la Historia de Usuario:** Como Candidato, quiero completar una entrevista automatizada en video, para que el reclutador pueda evaluarme de manera inicial sin necesidad de una entrevista en vivo.

**Criterios de Aceptación:**  
- **Dado que** he sido preseleccionado, **cuando** inicio la entrevista en video, **entonces** el sistema debería guiarme con preguntas predeterminadas.
- **Dado que** estoy completando la entrevista, **cuando** termino de responder, **entonces** el sistema debería guardar el video y notificar al reclutador.

**Notas Adicionales:**  
Usar LLM para guiar al candidato y estructurar las preguntas.

**Historias de Usuario Relacionadas:**  
HU003 (Filtrado Inicial de Candidatos), HU005 (Programación de Entrevistas)

---

### User Story 5

**ID:** HU005  
**Título de la Historia de Usuario:** Como Reclutador, quiero poder programar entrevistas para candidatos preseleccionados, para que pueda coordinar la disponibilidad del candidato y del equipo de entrevistas.

**Criterios de Aceptación:**  
- **Dado que** tengo candidatos preseleccionados, **cuando** elijo un candidato para entrevista, **entonces** el sistema debería permitirme seleccionar fecha y hora.
- **Dado que** deseo sincronizar los calendarios, **cuando** confirmo la entrevista, **entonces** el sistema debería enviar notificaciones al candidato y al equipo de entrevistas con la información de la cita.

**Notas Adicionales:**  
Considerar integración con calendarios (Google Calendar o similar) para gestionar horarios.

**Historias de Usuario Relacionadas:**  
HU004 (Entrevista Automática Guiada por LLM), HU006 (Evaluaciones Técnicas Automatizadas)

---

### User Story 6

**ID:** HU006  
**Título de la Historia de Usuario:** Como Candidato, quiero realizar una evaluación técnica enviada por el sistema, para que el reclutador pueda evaluar mis conocimientos específicos.

**Criterios de Aceptación:**  
- **Dado que** la evaluación está disponible, **cuando** inicio la prueba, **entonces** el sistema debería permitirme responder preguntas dentro de un tiempo límite.
- **Dado que** he completado la evaluación, **cuando** envío mis respuestas, **entonces** el sistema debería guardar mis respuestas y notificar al reclutador.

**Notas Adicionales:**  
Las evaluaciones deben ser configurables según el tipo de vacante.

**Historias de Usuario Relacionadas:**  
HU005 (Programación de Entrevistas), HU007 (Seguimiento de Proceso)

---

### User Story 7

**ID:** HU007  
**Título de la Historia de Usuario:** Como Reclutador, quiero ver el estado de cada candidato en el proceso de selección, para que pueda entender el avance de cada vacante y realizar ajustes.

**Criterios de Aceptación:**  
- **Dado que** tengo candidatos en diferentes etapas, **cuando** reviso el estado de cada uno, **entonces** debería ver si están en revisión, preselección, entrevista o evaluación.
- **Dado que** el candidato cambia de etapa, **cuando** actualizo el estado, **entonces** el sistema debería reflejar este cambio en el perfil del candidato.

**Notas Adicionales:**  
El sistema debe permitir personalizar las etapas del proceso de reclutamiento según las necesidades del puesto.

**Historias de Usuario Relacionadas:**  
HU006 (Evaluaciones Técnicas Automatizadas)



<br><br><br>
# Backlog de producto 

### **Metodología usada:** matriz de valor-esfuerzo

<br><br>

| ID     | Historia de Usuario | Valor | Esfuerzo | Prioridad     |
|--------|---------------------------------------------------------------------------------------------------------------------|-------|----------|------------------|
| **HU001** | Como Reclutador, quiero crear y publicar vacantes en múltiples plataformas, para que pueda atraer candidatos calificados y recibir sus aplicaciones en un solo lugar. | 5     | 3        | Ganar-Ganar      |
| **HU002** | Como Reclutador, quiero recibir y almacenar todas las aplicaciones de candidatos en un solo lugar, para que pueda revisarlas de manera centralizada y eficiente. | 5     | 2        | Ganar-Ganar      |
| **HU003** | Como Reclutador, quiero aplicar filtros iniciales a las aplicaciones recibidas, para que pueda identificar rápidamente a los candidatos que cumplen con los requisitos básicos de la vacante. | 4     | 3        | Ganar-Ganar      |
| **HU007** | Como Reclutador, quiero ver el estado de cada candidato en el proceso de selección, para que pueda entender el avance de cada vacante y realizar ajustes. | 4     | 4        | Proyectos Estratégicos |
| **HU005** | Como Reclutador, quiero poder programar entrevistas para candidatos preseleccionados, para que pueda coordinar la disponibilidad del candidato y del equipo de entrevistas. | 3     | 3        | Ganar-Ganar      |
| **HU004** | Como Candidato, quiero completar una entrevista automatizada en video, para que el reclutador pueda evaluarme de manera inicial sin necesidad de una entrevista en vivo. | 4     | 4        | Proyectos Estratégicos |
| **HU006** | Como Candidato, quiero realizar una evaluación técnica enviada por el sistema, para que el reclutador pueda evaluar mis conocimientos específicos. | 3     | 5        | Proyectos Estratégicos |
<br><br>
### Matriz esfuerzo-valor

![image](https://i.ibb.co/88W404f/output.png)
---
![image](https://i.ibb.co/Zgh1RR9/Matriz-de-Valor-Esfuerzo-para-Historias-de-Usuario-del-MVP.png)

<br><br><br>

# Tickets de trabajo



**HU001-TK01: Implementar formulario de creación de vacantes**  
Categoría: Característica

**Descripción:**  
- **Propósito:** Permitir a los reclutadores ingresar detalles básicos de una vacante en un formulario estructurado.
- **Detalles Específicos:** El formulario debe incluir campos para el título del puesto, descripción, ubicación, requisitos, y tipo de empleo (remoto/presencial). Estos campos deben ser obligatorios y validados en el frontend.

**Criterios de Aceptación:**  
- **Dado que** el reclutador está en la página de creación de vacantes, **cuando** completa el formulario con datos válidos, **entonces** debería poder guardar los datos sin errores.
- **Dado que** algún campo está incompleto o tiene errores, **cuando** el reclutador intenta guardar, **entonces** el sistema debería mostrar mensajes de error indicando los campos obligatorios y el formato correcto.

---

**HU001-TK02: Publicar vacantes en LinkedIn**  
Categoría: Característica

**Descripción:**  
- **Propósito:** Facilitar la publicación de las vacantes en plataformas externas para aumentar la visibilidad de los puestos.
- **Detalles Específicos:** Crear un sistema de integración con LinkedIn que permita que las vacantes creadas se publiquen automáticamente en LinkedIn. El sistema debe solicitar permisos de acceso y autenticación a LinkedIn en la primera conexión.

**Criterios de Aceptación:**  
- **Dado que** el reclutador ha creado una vacante, **cuando** selecciona LinkedIn como canal de publicación, **entonces** el sistema debería publicar automáticamente la vacante en la cuenta de LinkedIn autorizada.
- **Dado que** el reclutador no está autenticado en LinkedIn, **cuando** selecciona LinkedIn, **entonces** el sistema debería pedir autenticación antes de publicar la vacante.

---

**HU001-TK03: Implementar previsualización de vacante antes de publicación**  
Categoría: Característica

**Descripción:**  
- **Propósito:** Permitir al reclutador revisar los detalles de la vacante antes de su publicación para evitar errores o datos incompletos.
- **Detalles Específicos:** Agregar una pantalla de previsualización que muestre todos los datos de la vacante en el formato final que el candidato verá.

**Criterios de Aceptación:**  
- **Dado que** el reclutador ha ingresado todos los detalles de la vacante, **cuando** selecciona la opción de previsualización, **entonces** debería ver una página con toda la información tal como se verá en la plataforma pública.
- **Dado que** el reclutador identifica algún error en la previsualización, **cuando** regresa a la edición, **entonces** debería poder modificar los campos antes de la publicación.

---

**HU001-TK04: Configurar validaciones y formato de datos en el frontend**  
Categoría: Tarea Técnica

**Descripción:**  
- **Propósito:** Asegurar que los datos ingresados en el formulario de creación de vacantes cumplen con el formato requerido, mejorando la calidad de los datos.
- **Detalles Específicos:** Implementar validaciones en el frontend para cada campo del formulario (ej. longitud mínima y máxima, formato de texto, etc.).

**Criterios de Aceptación:**  
- **Dado que** el reclutador ingresa datos en el formulario, **cuando** estos no cumplen con el formato, **entonces** el sistema debería mostrar un mensaje de error en el campo correspondiente.
- **Dado que** los datos cumplen con el formato requerido, **cuando** el reclutador intenta guardarlos, **entonces** el sistema debería permitir el guardado sin mostrar errores.

---

**HU001-TK05: Investigación sobre integración de LinkedIn API para publicación automática**  
Categoría: Investigación (Spike)

**Descripción:**  
- **Propósito:** Entender los requisitos técnicos y permisos necesarios para integrar LinkedIn API, permitiendo la publicación automática de vacantes.
- **Detalles Específicos:** Realizar una investigación sobre las limitaciones y autenticaciones necesarias para la API de LinkedIn. Documentar los pasos y permisos necesarios, así como las posibles restricciones.

**Criterios de Aceptación:**  
- **Dado que** se requiere la integración con LinkedIn, **cuando** se completan los requisitos y documentación, **entonces** el equipo debería tener claro cómo realizar la autenticación y qué datos se pueden publicar automáticamente.
- **Dado que** existen limitaciones técnicas, **cuando** se identifica alguna restricción, **entonces** se debería incluir en la documentación para el equipo de desarrollo.

---

**HU001-TK06: Error en guardado de datos incompletos en el formulario de creación de vacantes**  
Categoría: Bug/Error

**Descripción:**  
- **Propósito:** Corregir un problema donde el sistema permite guardar formularios incompletos, resultando en datos erróneos en el sistema.
- **Detalles Específicos:** Revisar la lógica de validación en el backend para asegurar que todos los campos obligatorios deben estar completos antes de guardar.

**Criterios de Aceptación:**  
- **Dado que** el formulario está incompleto, **cuando** el reclutador intenta guardarlo, **entonces** el sistema debería impedir el guardado y mostrar mensajes de error para los campos faltantes.
- **Dado que** el formulario está completo, **cuando** el reclutador intenta guardarlo, **entonces** el sistema debería permitir el guardado sin errores.

---


### Estimación, asignación y priorización



| ID            | Título                                              | Categoría         | Estimación (Scrum Poker) | Prioridad         | Asignación | Sprint |
|---------------|------------------------------------------------------|-------------------|--------------------------|-------------------|------------|--------|
| HU001-TK01    | Implementar formulario de creación de vacantes       | Característica    | 5 puntos                 | Alta              | Dev 1      | 1      |
| HU001-TK04    | Configurar validaciones y formato de datos en frontend | Tarea Técnica  | 3 puntos                 | Alta              | Dev 2      | 1      |
| HU001-TK05    | Investigación sobre integración de LinkedIn API      | Investigación     | 2 puntos                 | Alta              | Dev 3      | 1      |
| HU001-TK02    | Publicar vacantes en LinkedIn                        | Característica    | 8 puntos                 | Media (dep. TK05) | Dev 1, 2   | 2      |
| HU001-TK03    | Implementar previsualización de vacante              | Característica    | 5 puntos                 | Media             | Dev 2      | 2      |
| HU001-TK06    | Error en guardado de datos incompletos               | Bug/Error         | 3 puntos                 | Crítica           | Dev 3      | 2      |


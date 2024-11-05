### User Story 1

**Como** manager de contratación, **quiero** recibir notificaciones automáticas sobre el estado de los candidatos **para** supervisar el proceso sin perder actualizaciones importantes.

**Descripción**: La funcionalidad permite que los managers de contratación reciban notificaciones en tiempo real sobre cambios o actualizaciones en el proceso de reclutamiento de cada candidato, asegurando que no se pierdan detalles importantes.

**Criterios de Aceptación**:

- **Dado que** soy un manager de contratación con acceso al sistema, **cuando** un candidato avance o cambie de estado en el proceso de selección, **entonces** recibiré una notificación automática (push, email o dentro de la plataforma).
- **Dado que** recibo notificaciones automáticas, **cuando** el sistema me notifique, **entonces** podré ver el cambio de estado y los detalles relevantes de cada candidato.

**Notas adicionales**:

- Las notificaciones deben ser configurables para evitar notificaciones excesivas.
- Se debe considerar la integración de notificaciones en dispositivos móviles para mayor flexibilidad.

---

### User Story 2

**Como** reclutador, **quiero** acceder a sugerencias de IA para seleccionar candidatos ideales **para** que el proceso de evaluación inicial sea más preciso y efectivo.

**Descripción**: Esta funcionalidad utiliza IA para sugerir candidatos que cumplan con los requisitos específicos de una vacante, ayudando a los reclutadores a priorizar y seleccionar a los candidatos con el perfil más adecuado.

**Criterios de Aceptación**:

- **Dado que** estoy revisando una lista de candidatos para una posición específica, **cuando** accedo a las recomendaciones de IA, **entonces** podré ver una lista ordenada de candidatos que mejor cumplen los criterios de la vacante.
- **Dado que** existen varios criterios en el perfil de la vacante, **cuando** aplico filtros específicos (habilidades, experiencia), **entonces** la IA adaptará las sugerencias en base a esos filtros.

**Notas adicionales**:

- La IA debe aprender y mejorar las recomendaciones en función de las elecciones de los reclutadores.
- Las sugerencias de IA deben ser opcionales y permitir la revisión manual de los candidatos.

---

### User Story 3

**Como** administrador del sistema, **quiero** configurar permisos y accesos para los usuarios en la plataforma **para** mantener la seguridad y privacidad de los datos de los candidatos.

**Descripción**: Esta funcionalidad permite a los administradores gestionar los niveles de acceso y permisos de los usuarios en el sistema, asegurando que solo personas autorizadas puedan acceder a la información sensible de los candidatos.

**Criterios de Aceptación**:

- **Dado que** soy un administrador del sistema, **cuando** configuro los permisos de un usuario, **entonces** solo podrá acceder a las áreas y funciones asignadas en su perfil.
- Los usuarios solo verán las opciones y secciones que estén habilitadas según su rol, evitando el acceso accidental a funcionalidades restringidas y mejorando la eficiencia de la interfaz.
- **Dado que** el usuario tenga un rol específico sin permisos para ciertas secciones, **cuando** acceda a la plataforma, **entonces** solo verá las opciones y secciones habilitadas para su rol, y no podrá visualizar las funcionalidades restringidas.
- **Dado que** un usuario intente acceder a una URL directa de una sección restringida, **cuando** no tenga el rol requerido, **entonces** el sistema deberá bloquear el acceso y redirigir al usuario a una página de acceso denegado.

**Notas adicionales**:

- La configuración de permisos debe permitir diferentes niveles de acceso: lectura, escritura, y administración.
- Se deben registrar los intentos de acceso fallidos para auditar la seguridad del sistema.
- Este cambio implica que el sistema oculte de la vista general las secciones restringidas, optimizando la interfaz y reduciendo la complejidad visual.

---

### User Story 4

**Como** manager de contratación, **quiero** visualizar informes y estadísticas sobre el proceso de selección **para** tomar decisiones basadas en datos y mejorar continuamente la estrategia de contratación.

**Descripción**: Esta funcionalidad permite que los managers de contratación accedan a informes detallados sobre el rendimiento del proceso de selección, como el tiempo promedio de contratación y el número de candidatos en cada fase.

**Criterios de Aceptación**:

- **Dado que** soy un manager de contratación, **cuando** accedo al panel de informes, **entonces** podré visualizar datos de rendimiento, como el número de candidatos entrevistados, rechazados y contratados.
- **Dado que** quiero evaluar la eficiencia del proceso, **cuando** consulte el tiempo promedio de contratación, **entonces** podré ver los tiempos por etapa y optimizar el proceso.

**Notas adicionales**:

- Los informes deben actualizarse en tiempo real para reflejar el estado actual del proceso de selección.
- Se debe considerar la exportación de datos en formato CSV o PDF para análisis externo.

---

### User Story 5

Como candidato, quiero cargar mi hoja de vida para que el sistema extraiga automáticamente los datos clave, de manera que solo necesite completar la información faltante.

**Descripción**:  El candidato puede subir su hoja de vida en formato de documento, y el sistema, mediante inteligencia artificial, analizará y extraerá automáticamente los datos clave, como experiencia laboral, educación, y habilidades. El candidato solo ingresará manualmente los datos faltantes o no reconocidos por el sistema.

**Criterios de Aceptación**:

- **Dado que** el candidato suba su hoja de vida en el formato compatible, **cuando** el sistema procese el documento, **entonces** deberá extraer información como nombre, experiencia laboral, educación, y habilidades, mostrando los datos extraídos en un formulario editable para verificación.
- **Dado que** el sistema detecte que faltan algunos datos en la hoja de vida o que estos no sean claros, **cuando** se complete la extracción, **entonces** solicitará al candidato ingresar los datos faltantes en campos individuales.

**Notas adicionales**:

- Se debe considerar la seguridad y encriptación de documentos personales adjuntados al perfil del candidato.
- Esta funcionalidad reduce el tiempo que el candidato invierte en completar su perfil y minimiza posibles errores en la transcripción manual de datos.
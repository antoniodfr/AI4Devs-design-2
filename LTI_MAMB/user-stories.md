
---
### 1. **Creación del Proyecto de Sistema ATS**
   - **Descripción**: Como **administrador del sistema**, quiero crear un proyecto base para el sistema ATS, configurando la infraestructura inicial, para que esté listo para la integración de módulos específicos del MVP.
   - **Criterios de Aceptación**:
     - Se ha creado un repositorio de código y estructura de carpetas.
     - El entorno de desarrollo está configurado con bases de datos y servidores necesarios.
     - Documentación inicial de configuración del entorno está disponible para el equipo.

### 2. **Configuración del Dashboard Centralizado de Candidatos**
   - **Descripción**: Como **reclutador**, quiero acceder a un dashboard centralizado que muestre a todos los candidatos en diferentes etapas del proceso de selección, para poder visualizarlos y gestionarlos de manera eficiente.
   - **Criterios de Aceptación**:
     - El dashboard muestra a todos los candidatos, con filtrado por etapa del proceso de selección.
     - La información básica de cada candidato (nombre, experiencia, estado) es visible desde el dashboard.
     - Los datos del dashboard se actualizan en tiempo real a medida que los candidatos avanzan en el proceso.

### 3. **Filtrado Automático de Candidatos con IA Básica**
   - **Descripción**: Como **reclutador**, quiero que el sistema use IA para filtrar automáticamente candidatos con base en palabras clave y criterios específicos, para reducir el tiempo en la selección inicial de candidatos.
   - **Criterios de Aceptación**:
     - El sistema realiza un filtrado automático de candidatos basado en palabras clave predefinidas (ej. habilidades requeridas).
     - Los candidatos filtrados cumplen con al menos el 70% de los criterios seleccionados.
     - La interfaz permite al reclutador ver los candidatos recomendados y rechazados con base en los filtros aplicados.

### 4. **Publicación de Ofertas de Empleo en Múltiples Plataformas**
   - **Descripción**: Como **reclutador**, quiero publicar ofertas de empleo desde el sistema en múltiples plataformas y redes sociales, para ampliar el alcance de la oferta de trabajo.
   - **Criterios de Aceptación**:
     - La funcionalidad permite publicar ofertas en al menos 3 plataformas externas.
     - El reclutador puede seleccionar la fuente para cada oferta y ver un resumen de candidatos por fuente.
     - La oferta de trabajo contiene los campos necesarios (título, descripción, requisitos) y está correctamente sincronizada en las plataformas seleccionadas.

### 5. **Interacción con Chatbot Básico para Candidatos**
   - **Descripción**: Como **candidato**, quiero interactuar con un chatbot que me guíe a través del proceso de aplicación y me responda preguntas comunes, para facilitar y hacer más eficiente mi experiencia en la aplicación.
   - **Criterios de Aceptación**:
     - El chatbot puede responder al menos 5 preguntas comunes (ej. estado de la aplicación, requisitos del trabajo).
     - El chatbot guía al candidato en el proceso de aplicación, mostrando los pasos a seguir.
     - La interacción con el chatbot es fluida y el candidato puede obtener respuestas en menos de 5 segundos.

### 6. **Análisis Predictivo Básico de Ajuste Candidato-Empresa**
   - **Descripción**: Como **reclutador**, quiero que el sistema realice un análisis predictivo del ajuste candidato-empresa utilizando IA, para recibir una estimación inicial de los candidatos con mayor potencial.
   - **Criterios de Aceptación**:
     - El sistema asigna una puntuación de ajuste (matching score) a cada candidato, con base en criterios de experiencia y habilidades.
     - El puntaje de ajuste aparece junto a cada candidato en el dashboard.
     - El sistema puede ordenar a los candidatos por puntaje de ajuste, permitiendo al reclutador visualizar los mejores candidatos en la parte superior.

### 7. **Notificaciones y Seguimiento de Candidatos por Etapa**
   - **Descripción**: Como **reclutador**, quiero recibir notificaciones sobre los cambios en el estado de los candidatos y poder hacer seguimiento de cada uno por etapa, para gestionar de manera efectiva el proceso de selección.
   - **Criterios de Aceptación**:
     - El sistema notifica al reclutador cuando un candidato cambia de etapa (por ejemplo, “Filtrado completado”, “Entrevista programada”).
     - El reclutador puede actualizar el estado de un candidato y el dashboard se actualiza en tiempo real.
     - Existe un registro de las etapas completadas para cada candidato, visible desde su perfil.

### 8. **Funcionalidad Básica de Reportes de Rendimiento de Reclutamiento**
   - **Descripción**: Como **gerente de RRHH**, quiero ver reportes básicos sobre el rendimiento del proceso de reclutamiento (por ejemplo, tiempo de contratación promedio, número de candidatos por fuente) para obtener insights sobre la eficiencia del proceso.
   - **Criterios de Aceptación**:
     - Los reportes muestran métricas clave como tiempo promedio de contratación y número de candidatos por fuente.
     - Los datos en el reporte se actualizan semanalmente o en tiempo real.
     - Los reportes pueden exportarse en formato PDF o Excel para revisiones externas.
---

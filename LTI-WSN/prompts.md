# Propmts usados en el proceso de HU y priorización

## 0. Prompt de contexto
```Propmt
Quiero que analices la base de conocimiento que te anexare, no me respondas, solo quiero que tengas el contexto del sistema de información que estoy diseñando.
```
## 1. Prompts para HU

```Markdown
Con el objetivo de desarrollar nuestro MVP de manera que cumpla con las expectativas y necesidades de los usuarios finales, es requerido generar 10 historias de usuario principales utilizando la información de contexto cargada al chat anteriormente. 
Este trabajo será ejecutado por un Product Manager y un Business Analyst, quienes se encargarán de las siguientes tareas: 


1. **Análisis del Contexto**:
   - Examinar detenidamente la información de contexto cargada para extraer información relevante sobre las necesidades, problemas y características discutidas. 
   - Identificar los requerimientos clave que los usuarios esperan que el producto satisfaga.

2. **Formulación de Historias de Usuario**:
   - Redactar 10 historias de usuario siguiendo la estructura detallada proporcionada: 
     - **Título de la Historia de Usuario**: Un breve resumen que capture la esencia de la necesidad.
     - **Como [rol del usuario]**,
     - **Quiero [acción que desea realizar el usuario]**,
     - **Para que [beneficio que espera obtener el usuario]**.
     - **Criterios de Aceptación**: Incluir al menos cuatro detalles específicos de funcionalidad que deben ser cumplidos para que la historia sea aceptada. 
     - **Notas Adicionales**: Cualquier consideración adicional que pueda influir en el desarrollo o implementación.
     - **Historias de Usuario Relacionadas**: Indicar conexiones con otras historias para facilitar la comprensión del flujo y dependencias del producto.

3. **Validación y Priorización**:
   - Confirmar que cada historia de usuario sea relevante y crítica para los objetivos del MVP.
   - Ordenar las historias por prioridad basándose en su impacto en el valor principal que el producto debe entregar.

4. **Documentación y Revisión**:
   - Documentar las historias de usuario de forma clara y accesible para revisión por el equipo de desarrollo y otros stakeholders.
   - Revisar y ajustar las historias basándose en el feedback recibido para asegurar que son completas y ejecutables.
```

## 2. Propmpts para priorización
### 2.1 Metodo MoSCoW
```prompt
Continuando con el desarrollo del MVP y basándonos en las historias de usuario previamente definidas, el siguiente paso es elaborar y priorizar el backlog de producto. Este proceso será guiado por el método MoSCoW para asegurar una efectiva priorización de las tareas. El trabajo será realizado por el equipo de gestión de producto, y consiste en las siguientes tareas:

1. **Compilación del Backlog**:
   - Revisar todas las historias de usuario generadas anteriormente y listarlas en un documento para formar el backlog inicial del producto.
   - Asegurarse de que cada historia de usuario esté claramente definida con su título, descripción, criterios de aceptación, y cualquier otra información relevante.

2. **Aplicación del Método MoSCoW**:
   - Clasificar cada historia de usuario dentro de las categorías del método MoSCoW:
     - **Must Have (M)**: Historias críticas sin las cuales el producto no puede ser lanzado.
     - **Should Have (S)**: Historias importantes que deben incluirse en el lanzamiento si es posible, pero que pueden ser pospuestas si es necesario.
     - **Could Have (C)**: Historias deseables que, aunque aportarían valor, no son esenciales y podrían incluirse en futuras versiones.
     - **Won’t Have This Time (W)**: Historias que no se abordarán en este ciclo de lanzamiento.

3. **Documentación en Markdown**:
   - Formatear el backlog priorizado en Markdown para facilitar su revisión y referencia. El formato debe incluir:
     - **Título de la Historia**
     - **Prioridad MoSCoW**
     - **Descripción Detallada**
     - **Criterios de Aceptación**
     - **Notas Adicionales** (si las hay)

markdown
## Backlog de Producto Priorizado

### Must Have (M)
- **Historia de Usuario 1**: 
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
  - **Criterios de Aceptación**:
    - [Detalle específico de funcionalidad]
    - [Detalle específico de funcionalidad]

### Should Have (S)
- **Historia de Usuario 2**: 
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
  - **Criterios de Aceptación**:
    - [Detalle específico de funcionalidad]

### Could Have (C)
- **Historia de Usuario 3**: 
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].

### Won’t Have This Time (W)
- **Historia de Usuario 4**: 
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
```

#### Conclusiones
El uso de este prompt me pareció efectivo por la velocidad en la implementación, la claridad en la priorización de tareas y la calidad de los resultados obtenidos. Además, fue invaluable contar con la posibilidad de simular diferentes escenarios en tiempos muy cortos

### 2.2 Metodo Valor y costo
```Propmt
Tras desarrollar las historias de usuario para nuestro MVP, el siguiente paso es priorizar el backlog utilizando un enfoque basado en el valor y el costo. Este método garantiza que priorizamos las tareas que proporcionan el mayor valor al usuario final con el menor costo de implementación. Este proceso será llevado a cabo por un equipo de Product Managers y Business Analysts y consistirá en las siguientes tareas:

1. **Evaluación de Valor**:
   - Asignar a cada historia de usuario un puntaje de valor basado en el impacto esperado sobre los usuarios y los beneficios para el negocio. Considerar factores como la satisfacción del cliente, la retención, la adquisición de nuevos usuarios y la ventaja competitiva.

2. **Estimación de Costo**:
   - Evaluar el costo relativo de implementar cada historia de usuario. Esto incluye el tiempo estimado de desarrollo, los recursos necesarios y cualquier otro costo asociado como tecnología o licencias.

3. **Clasificación y Priorización**:
   - Utilizar una matriz de priorización para clasificar las historias de usuario según su valor y costo. Priorizar aquellas con alto valor y bajo costo para maximizar el retorno sobre la inversión (ROI).
   - Las historias de usuario que presenten un alto costo y bajo valor deberán reconsiderarse o modificarse para reducir costos o aumentar su valor.

4. **Documentación en Markdown**:
   - Documentar el proceso y los resultados en un formato estructurado de Markdown, facilitando la comunicación y revisión. Cada historia de usuario debe incluir:
     - **Título de la Historia**
     - **Puntaje de Valor**
     - **Estimación de Costo**
     - **Prioridad** (Alta, Media, Baja)
     - **Descripción Detallada**
     - **Criterios de Aceptación**
     - **Notas Adicionales** (si las hay)

markdown
## Backlog de Producto Priorizado por Valor y Costo

### Alta Prioridad (Alto Valor, Bajo Costo)
- **Historia de Usuario 1**: 
  - **Valor**: 9/10
  - **Costo**: Bajo
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
  - **Criterios de Aceptación**:
    - [Detalle específico de funcionalidad]
    - [Detalle específico de funcionalidad]

### Media Prioridad (Medio Valor, Medio Costo)
- **Historia de Usuario 2**: 
  - **Valor**: 7/10
  - **Costo**: Medio
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].

### Baja Prioridad (Bajo Valor, Alto Costo)
- **Historia de Usuario 3**: 
  - **Valor**: 4/10
  - **Costo**: Alto
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
```
#### Conclusiones
La ejecución del prompt para el Método Valor y Costo" fue efectiva, ya que me  permitió evaluar rápidamente cada funcionalidad en términos de su impacto y el esfuerzo necesario para implementarla. Este enfoque facilita la toma de decisiones bien informadas, priorizando elementos de alto valor con bajo costo y optimizando así nuestros recursos. 

### 2.3 Metodo Kano
```prompt
Con el desarrollo del MVP en marcha y las historias de usuario ya definidas, es crucial priorizar el backlog de producto utilizando el Método Kano para evaluar cómo cada característica impacta en la satisfacción del cliente. Este método categoriza las características en básicas, de rendimiento y de encanto. El proceso será llevado a cabo por un equipo de Product Managers y Business Analysts y consistirá en las siguientes etapas:

1. **Categorización de Características**:
   - Revisar cada historia de usuario y categorizarla según el Método Kano:
     - **Características Básicas**: Necesarias para que el producto funcione adecuadamente y evitar la insatisfacción si faltan.
     - **Características de Rendimiento**: Aquellas que aumentan la satisfacción del cliente de manera proporcional a su nivel de implementación.
     - **Características de Encanto**: No necesariamente esperadas pero que pueden aumentar significativamente la satisfacción del cliente cuando se presentan.

2. **Evaluación de Impacto**:
   - Evaluar cómo cada característica afecta la satisfacción del cliente y la diferenciación del producto en el mercado.

3. **Documentación en Markdown**:
   - Documentar el proceso y los resultados utilizando el formato Markdown, lo que incluye:
     - **Título de la Historia**
     - **Categoría Kano**
     - **Descripción Detallada**
     - **Criterios de Aceptación**
     - **Notas Adicionales** (si las hay)

markdown
## Backlog de Producto Priorizado según el Método Kano

### Características Básicas
- **Historia de Usuario 1**: 
  - **Categoría**: Básica
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
  - **Criterios de Aceptación**:
    - [Detalle específico de funcionalidad]

### Características de Rendimiento
- **Historia de Usuario 2**: 
  - **Categoría**: Rendimiento
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
  - **Criterios de Aceptación**:
    - [Detalle específico de funcionalidad]

### Características de Encanto
- **Historia de Usuario 3**: 
  - **Categoría**: Encanto
  - **Descripción**: Como [rol], quiero [acción], para que [beneficio].
```
#### Conclusiones
El diseño y ejecución de este prompt me parecio efectivo en la medida que pude incluir un elemento mas de analisis en el proceso, obteniendo rapidamente un enfoque basado en las funcionalidades que generan mayor satisfacción en los usuarios, diferenciando entre necesidades básicas, de desempeño y atractivas

## 3. Prompts para Tickets
```prompt
Basado en la historia de usuario "Automatización de Tareas de Reclutamiento", necesitamos desarrollar tickets de trabajo técnicos que definan claramente las tareas a realizar para implementar esta funcionalidad en nuestro sistema. Este proceso será ejecutado por el equipo de desarrollo durante una reunión de planificación técnica y consistirá en las siguientes etapas:

1. **Descomposición de la Historia de Usuario**:
   - Dividir la historia de usuario en componentes lógicos menores que sean manejables y ejecutables por el equipo de desarrollo.
   - Identificar los aspectos técnicos clave que necesitan ser abordados para cada componente.

2. **Definición de Tareas Técnicas**:
   - Describir detalladamente las tareas técnicas necesarias para cada componente identificado. Esto incluye:
     - **Desarrollo de Interfaces**: Definir las interfaces de usuario necesarias para la automatización de las tareas de reclutamiento.
     - **Integración de Sistemas**: Especificar cómo se integrará la nueva funcionalidad con sistemas existentes, como bases de datos de candidatos o plataformas de publicación de empleos.
     - **Pruebas y Validación**: Desarrollar pruebas para asegurar que la funcionalidad cumple con los criterios de aceptación especificados.

3. **Especificación Técnica**:
   - Para cada tarea, especificar los requisitos técnicos, incluyendo lenguajes de programación, herramientas, y librerías a utilizar.
   - Definir los criterios de aceptación técnicos para asegurar que la tarea se completa correctamente.

4. **Priorización y Asignación**:
   - Priorizar las tareas basadas en su dependencia técnica y urgencia.
   - Asignar las tareas a los miembros del equipo con las habilidades adecuadas para llevarlas a cabo.

5. **Documentación en Markdown**:
   - Documentar cada ticket de trabajo en un formato Markdown para asegurar que toda la información relevante esté accesible y sea fácil de seguir. Incluir:
     - **Título del Ticket**: Claramente definido para reflejar la tarea a realizar.
     - **Descripción Detallada**: Explicar lo que se debe hacer y por qué.
     - **Requisitos Técnicos**: Detallar los recursos y tecnologías necesarios.
     - **Criterios de Aceptación Técnicos**: Listar las condiciones que debe cumplir la tarea para considerarse completa.

markdown
## Tickets de Trabajo para Automatización de Tareas de Reclutamiento

### Ticket 1: Diseño de la Interfaz de Usuario para la Gestión de Candidatos
- **Descripción**: Desarrollar interfaces de usuario para permitir a los reclutadores gestionar y filtrar candidatos automáticamente.
- **Requisitos Técnicos**: ReactJS, APIs RESTful.
- **Criterios de Aceptación Técnicos**: La interfaz debe permitir filtrar candidatos por habilidades, experiencia y ubicación.

### Ticket 2: Integración con Sistema de Gestión de Candidatos
- **Descripción**: Integrar la nueva funcionalidad de automatización con el sistema de gestión de candidatos existente.
- **Requisitos Técnicos**: Java, Spring Boot, API REST.
- **Criterios de Aceptación Técnicos**: La integración debe funcionar sin interrupciones y sincronizar los datos en tiempo real.

### Ticket 3: Pruebas de Validación
- **Descripción**: Desarrollar pruebas automatizadas para validar la funcionalidad de automatización de reclutamiento.
- **Requisitos Técnicos**: Selenium, JUnit.
- **Criterios de Aceptación Técnicos**: Todas las pruebas deben pasar satisfactoriamente antes del lanzamiento.
```


## 4. Prompt para estimación de Tickets de trabajo - Metodologia T-Shirt Sizing

```prompt
Ahora que hemos generado los tickets de trabajo para la automatización de tareas de reclutamiento, es necesario estimar el esfuerzo requerido para cada ticket utilizando la metodología de "T-Shirt Sizing". Este método nos ayudará a categorizar los tickets en diferentes tamaños que representan el nivel de esfuerzo necesario para completar cada tarea. El proceso de estimación será llevado a cabo por el equipo de desarrollo y consistirá en las siguientes etapas:

1. **Revisión de Tickets de Trabajo**:
   - Comenzar con una revisión detallada de cada ticket generado previamente. Asegurarse de que cada miembro del equipo comprenda los requisitos y el alcance de cada tarea.

2. **Clasificación por Tamaños**:
   - Discutir como equipo y asignar un tamaño de 'camiseta' a cada ticket de trabajo, donde los tamaños posibles son:
     - **XS (Extra Small)**: Tareas muy simples que requieren poco esfuerzo y tiempo.
     - **S (Small)**: Tareas que son un poco más complejas pero aún simples y rápidas de completar.
     - **M (Medium)**: Tareas de complejidad y esfuerzo medio.
     - **L (Large)**: Tareas que requieren un esfuerzo considerable y más tiempo para completar.
     - **XL (Extra Large)**: Proyectos grandes que requieren un esfuerzo significativo y una cantidad sustancial de tiempo.

3. **Documentación en Markdown**:
   - Documentar las estimaciones de tamaño para cada ticket en formato Markdown. Esto debe incluir una breve justificación para la elección del tamaño, basada en la discusión del equipo.

markdown
## Estimaciones de T-Shirt Sizing para Tickets de Trabajo

### XS (Extra Small)
- **Ticket 1**: [Breve descripción del ticket]
  - **Justificación**: Requiere cambios mínimos y no depende de otros sistemas.

### S (Small)
- **Ticket 2**: [Breve descripción del ticket]
  - **Justificación**: Implica una interfaz sencilla con pocos campos.

### M (Medium)
- **Ticket 3**: [Breve descripción del ticket]
  - **Justificación**: Necesita integración entre sistemas existentes.

### L (Large)
- **Ticket 4**: [Breve descripción del ticket]
  - **Justificación**: Requiere desarrollo de nuevas funciones y pruebas exhaustivas.

### XL (Extra Large)
- **Ticket 5**: [Breve descripción del ticket]
  - **Justificación**: Implica una revisión completa del proceso de reclutamiento, integración y automatización extensiva.
```
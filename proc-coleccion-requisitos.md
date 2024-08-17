
Casos de Prueba
A continuación, te dejo ejemplos de casos de prueba basados en los casos de uso:
Caso de Prueba CP-001: Verificar Registro Completo
•	Objetivo: Verificar que el sistema permita registrar un nuevo producto correctamente.
•	Requerimiento Relacionado: Registro de Nuevos Productos (UC-01).
•	Pasos:
1.	Navegar a la página de registro de productos.
2.	Completar todos los campos obligatorios (nombre, código, cantidad, precio unitario, fecha de ingreso, fecha de vencimiento, descripción).
3.	Presionar el botón "Guardar".
•	Condición Inicial: Sistema sin errores, campos obligatorios en blanco.
•	Resultado Esperado: El producto se registra exitosamente, y el sistema muestra un mensaje de confirmación.


### Plantilla de Gestion de requemientos.
```mermaid
flowchart TD
    A[Inicio del Proyecto] --> B[Identificación del Cliente o Usuario]
    B --> C[Definición de Objetivos]
    C --> D[Recolección de Información con stakeholders]

    D --> D1[Entrevistas y Encuestas]
    D --> D2[Revisión de Documentación Existente]
    D --> D3[Observación Directa]

    D1 --> E[Análisis de Requisitos]
    D2 --> E
    D3 --> E

    E --> E1[Identificación de Requisitos Funcionales y No Funcionales]
    E --> E2[Priorización de Requisitos]

    E1 --> F[Documentación de Requisitos -  Jira]
    E2 --> E3["-Entender objetivo negocio.
    - Involucrar a los stakeholdres. 
    -Clasificar requisitos. 
    -Impacto y valor. 
    - Utilizacion del metodo MoSCoW."]
    E3 --> F 

    F --> F1[Creación de Especificaciones]
    F --> F2[Validación y Aprobación de Requisitos]

    F2 --> G[Gestión de Cambios en los Requisitos]

    G --> G1[Establecimiento de un Proceso de Control de Cambios]
    G --> G2[Comunicación de Cambios]
    G1 --> G3["-Evaluacion
    -Analisis de impacto
    -Revision y aprobacion" ]

    G2 --> H[Finalización del Proceso]

    H --> H1[Revisión Final]
    H --> H2[Aprobación y Cierre]

```

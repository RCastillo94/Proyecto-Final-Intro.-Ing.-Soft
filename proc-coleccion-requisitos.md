### proceso de recoleccoion de requisitos 

```mermaid
flowchart TD;
    A[Inicio] --> B[Leer configuración desde config.json];
    B --> C[Establecer conexión a la base de datos SQL];
    C -->|Conexión exitosa| D[Ejecutar consulta SQL y cargar datos en DataFrame];
    C -->|Conexión fallida| E[Mostrar error y cerrar conexión];
    D --> F[Procesar datos];
    F --> G[Filtrar datos por fecha y eliminar filas no deseadas];
    G --> H[Guardar datos procesados en un archivo Excel];
    H --> I[Llamar a la función send_email con la ruta del archivo];
    I --> J[Crear contenedor de mensaje];
    J --> K[Adjuntar archivo Excel al correo];
    K --> L[Conectar al servidor SMTP];
    L -->|Conexión exitosa| M[Enviar correo electrónico];
    L -->|Conexión fallida| N[Mostrar error de envío];
    M --> O[Mostrar mensaje de éxito];
    O --> P[Fin];

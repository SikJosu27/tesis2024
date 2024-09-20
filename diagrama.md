```mermaid
graph TD
    A[Inicio del Servicio] --> B[Proceso de Reserva]
    B --> C[Antes de la Llegada]
    C --> D[Durante la Estancia]
    D --> E[Fin de la Estancia]
    E --> F[Post-Estancia]
    
    B --> G[Grado de Estandarización]
    C --> G
    D --> G
    E --> G
    
    A --> H[Bienes Físicos]
    C --> H
    D --> H
    E --> H
    
    B --> I[Servicios Intangibles]
    C --> I
    D --> I
    E --> I
    
    B --> J[Nivel de Contacto con el Cliente]
    D --> J

```mermaid
graph TD
    A[Inicio del Servicio] --> B[Proceso de Reserva]
    B --> C[Antes de la Llegada]
    C --> D[Durante la Estancia]
    D --> E[Fin de la Estancia]
    E --> F[Post-Estancia]
    
    %% Grado de Estandarización
    subgraph Estandarización
        B1[Proceso Estandarizado de Reserva] --> G[Grado de Estandarización]
        C1[Instrucciones Claras al Cliente] --> G
        D1[Protocolo de Servicio Durante Estancia] --> G
        E1[Proceso de Check-out Estandarizado] --> G
        F1[Evaluaciones Post-Estancia Estandarizadas] --> G
    end
    
    %% Bienes Físicos
    subgraph Bienes Físicos
        H1[Confirmación de Equipamiento en Reserva] --> H[Bienes Físicos]
        C2[Entrega de Bienes Físicos Predefinidos] --> H
        D2[Acceso a Instalaciones Físicas] --> H
        E2[Recuperación de Bienes Físicos] --> H
    end
    
    %% Servicios Intangibles
    subgraph Servicios Intangibles
        I1[Atención al Cliente en el Proceso de Reserva] --> I[Servicios Intangibles]
        C3[Comunicación Previa con el Cliente] --> I
        D3[Atención Personalizada Durante la Estancia] --> I
        F2[Seguimiento y Retroalimentación del Cliente] --> I
    end
    
    %% Nivel de Contacto con el Cliente
    subgraph Contacto con el Cliente
        B2[Interacción Inicial con el Cliente] --> J[Nivel de Contacto con el Cliente]
        C4[Interacción Durante la Planificación] --> J
        D4[Interacción Directa Durante la Estancia] --> J
        E3[Interacción al Finalizar la Estancia] --> J
        F3[Encuestas y Seguimiento] --> J
    end

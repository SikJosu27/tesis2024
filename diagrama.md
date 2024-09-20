```mermaid
graph TD
    A[Inicio] --> B[Evaluación de requisitos]
    B --> C{Decisión}
    C -->|Sí| D[Diseño del sistema de servicio]
    C -->|No| E[Revisión de requerimientos]
    D --> F[Implementación]
    E --> B

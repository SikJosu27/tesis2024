graph TB
    A[Ser básico (central)] --> B[Producto esencial (real)]
    B --> C[Servicio aumentado]
    
    subgraph Dimensiones de Calidad
        D1[Fiabilidad] 
        D2[Capacidad de Respuesta] 
        D3[Seguridad] 
        D4[Empatía] 
        D5[Tangibilidad]
    end
    
    A --> D5
    B --> D1
    B --> D2
    C --> D3
    C --> D4
    C --> D5
    
    %% Leyenda
    classDef service fill:#d9e8ff,stroke:#1c6ea4,stroke-width:2px;
    classDef quality fill:#fff3e6,stroke:#d96c1a,stroke-width:2px;
    
    A:::service
    B:::service
    C:::service
    
    D1:::quality
    D2:::quality
    D3:::quality
    D4:::quality
    D5:::quality

# Estructura IT/OT y Flujo de IA en Textil Innova S.A.

El siguiente diagrama representa cómo se conectan los sistemas de negocio (IT) con los procesos de fábrica (OT), mostrando el papel de la Inteligencia Artificial como eje central para optimizar la producción y la atención al cliente:

```mermaid
graph TD
    subgraph IT [Área de Negocio - IT]
        A[Plataforma E-commerce & Ventas] -->|Datos de demanda y pedidos| B(IA Analítica Predictiva)
        C[Portal Atención al Cliente] <-->|Respuestas 24/7| D(Chatbot IA Generativa)
        D -->|Tendencias y consultas| B
    end

    subgraph OT [Área de Planta - OT]
        E[Sensores IIoT en Telares y Máquinas] -->|Vibración y temperatura| F(IA Mantenimiento Predictivo)
        G[Cámaras Visión Artificial] -->|Detección de defectos| F
        H[Línea de Corte y Confección]
    end

    B ==>|Órdenes de producción ajustadas| H
    F ==>|Alertas preventivas y ajuste de ritmo| H
    H -->|Métricas de rendimiento| E
```

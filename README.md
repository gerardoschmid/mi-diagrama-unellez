# Organigrama de la UNELLEZ

Aquí está el organigrama de la universidad:

```mermaid
graph TD
    A[Consejo Superior] --> B[Rector]
    B --> C[Vicerrectorado Académico]
    B --> D[Vicerrectorado Administrativo]
    B --> E[Vicerrectorado de Producción Agrícola]
    
    C --> C1[Dirección de Docencia]
    C --> C2[Dirección de Investigación y Postgrado]
    C --> C3[Dirección de Extensión]
    
    D --> D1[Dirección de Planificación]
    D --> D2[Dirección de Recursos Humanos]
    D --> D3["Dirección de Servicios Generales <br>(Mantenimiento/Infraestructura)"]
    
    E --> E1[Dirección de Producción Animal]
    E --> E2[Dirección de Producción Vegetal]
    
    B --> F[Sedes Territoriales]
    F --> F1[Barinas (Rectoral)]
    F --> F2[Guanare]
    F --> F3[San Carlos]
    F --> F4[Guasdualito]
    
    F1 --> F11[Decanato Ciencias del Agro]
    F1 --> F12[Decanato Ingeniería]
    
    B --> G[Dependencias Adscritas]
    G --> G1[Secretaría General]
    G --> G2[DTIC (Tecnología)]
    G --> G3["Dirección de Cultura y Deporte <br>(Domo Deportivo)"]

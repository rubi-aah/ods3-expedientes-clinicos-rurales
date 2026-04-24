# Diagrama de Componentes

```mermaid
graph TD
    UI[Interfaz de Usuario]
    Auth[Módulo de Autenticación]
    Data[Gestión de Datos]
    Sync[Sincronización]
    DB[(Base de Datos Local)]
    Cloud[(Servidor en la Nube)]

    UI --> Auth
    UI --> Data
    Data --> DB
    Data --> Sync
    Sync --> Cloud

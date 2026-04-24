# Diagrama de Contexto

```mermaid
graph TD
    Paciente --> Sistema
    Medico --> Sistema
    Sistema --> BaseDatosLocal
    Sistema --> ServidorCentral

    BaseDatosLocal --> Sistema
    ServidorCentral --> Sistema

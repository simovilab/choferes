---
layout: image
side: right
image: /b_grilla.png
title: bUCR
kicker: Plan piloto
---

- Primer sistema inteligente de transporte público del país
- Pequeño laboratorio de pruebas para investigación y desarrollo
- Gestión integral de la información para las personas usuarias

---
layout: two-cols
kicker: Sistemas tecnológicos
title: Información del transporte público
---

<img src="/databus.png" width="200" />

<br/>

Productor de datos estandarizados

```mermaid
flowchart LR
    A((Databús)) --> B[/GTFS/]
    C[Google Maps]
    D[Otros]
    B --> C
    B --> D

```

::right::

<img src="/infobus.png" width="184" />

<br/>

Consumidor de datos estandarizados

```mermaid
flowchart LR
    A[/GTFS/] --> B((Infobús))
    C[Información estática]
    D[Información en tiempo real]
    B --> C
    B --> D
```

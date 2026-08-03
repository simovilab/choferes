---
layout: diagram
kicker: Su aporte al sistema
title: De cada viaje a la información pública
note: Con Databús App, el operador marca el <strong>inicio y el fin</strong> de cada viaje.
---

```mermaid
%%{init: {'themeVariables': {'fontSize': '36px'}}}%%
flowchart LR
  C[Operador] --> A(Databús App)
  A --> D((Databús))
  D --> I((Infobús))
  I --> W[/Usuarios/]
```

---
layout: steps
kicker: ¿Qué hace el operador en la app?
title: El flujo de un viaje, paso a paso
steps:
  - title: Configurar viaje
    desc: Ruta, recorrido y tipo de viaje
    icon: "lucide:list-checks"
  - title: Confirmar
    desc: Revisar los datos antes de salir
    icon: "lucide:check"
  - title: Iniciar viaje
    desc: 
    icon: "lucide:play"
  - title: Finalizar viaje
    desc:
    icon: "lucide:square"
---

---
layout: define
kicker: Demo
term: Demo
definition: Jae will <span class="accent2">cook</span>.
points:
  - Demo 1
  - Demo 2
  - Demo 3
---

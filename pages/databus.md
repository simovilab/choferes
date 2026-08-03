---
layout: define
kicker: Databús
term: ¿Qué es Databús?
definition: El sistema que convierte <span class="accent2">lo que hace el bus</span> en información pública.
points:
  - Recibe la señal del equipo a bordo de cada bus
  - Procesa la información relvante al viaje
  - Publica los datos en un formato estándar (GTFS) cada <span class="accent2">15s</span>
---
---
layout: panels
kicker: Databús
title: ¿Qué datos recogemos? 
panels:
  - icon: "lucide:map-pin"
    title: Ubicación
    items:
      - Posición del bus en la ruta
      - Velocidad y sentido de marcha
  - icon: "lucide:users"
    title: Ocupación
    items:
      - Cuánto espacio queda disponible
      - Se calcula en el servidor
  - icon: "lucide:route"
    title: Avance del viaje
    items:
      - Cuál es la próxima parada
      - A qué hora se estima llegar
  - icon: "lucide:bus"
    title: Identificación
    items:
      - Cuál bus y cuál ruta
      - A qué viaje corresponde
---

---
layout: vs
kicker: Sobre la privacidad
title: Qué se recopila y qué no (OPCIONAL)
label: "vs"
left:
  title: Sí se recopila
  items:
    - Ubicación del bus
    - Ocupación de asientos
    - Avance del viaje
    - Inicio y fin del viaje
right:
  title: No se recopila
  items:
    - Datos personales del operador
    - Audio ni video
    - Uso del teléfono
    - Ubicación fuera del viaje
---
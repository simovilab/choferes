---
layout: define
kicker: Databús
term: ¿Qué es Databús?
definition: El sistema que convierte <span class="accent2">el estado del bus</span> en datos públicos.
points:
  - Recibe la <span class="accent2">señal GPS</span> de cada bus
  - Procesa los <span class="accent2">datos relevantes</span> al viaje
  - Publica los datos en el formato estándar <span class="accent2">GTFS cada 15 s</span>
---

---
layout: panels
kicker: Databús
title: ¿Qué datos recogemos?
panels:
  - icon: "lucide:bus"
    title: Identificación
    items:
      - Cuál bus y cuál ruta
      - A qué viaje corresponde
  - icon: "lucide:map-pin"
    title: Ubicación
    items:
      - Posición del bus en la ruta
      - Velocidad y sentido de marcha
  - icon: "lucide:users"
    title: Ocupación
    items:
      - Cuánto espacio queda disponible
      - <span class="font-italic">No implementado todavía</span>
  - icon: "lucide:route"
    title: Avance del viaje
    items:
      - Cuál es la próxima parada
      - Hora estimada de llegada
---

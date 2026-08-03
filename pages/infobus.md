---
layout: default
kicker: Infobús
title: Información en tiempo real
---

<div
  class="h-full flex items-center justify-center"
  style="transform: translateY(70px);"
>

<div class="w-full flex items-center justify-center gap-4">

<div
  class="p-7 rounded-xl border border-orange-500/40 bg-white/5 shrink-0"
  style="width: 440px; min-height: 240px;"
>
  <div class="w-full flex justify-center mb-4 text-orange-400" style="font-size: 58px;">
    <carbon:data-base />
  </div>

  <div class="text-4xl font-bold text-orange-400 mb-3">
    Toma los datos
  </div>

  <div class="text-2xl leading-relaxed text-white">
    Procesa los horarios y la información en tiempo real (GTFS) del sistema de buses.
  </div>
</div>

<div
  class="opacity-80 shrink-0 flex items-center justify-center"
  style="font-size: 80px;"
>
  <carbon:arrow-right />
</div>

<div
  class="p-7 rounded-xl border border-emerald-500/40 bg-white/5 shrink-0"
  style="width: 440px; min-height: 240px;"
>
  <div class="w-full flex justify-center mb-4 text-emerald-400" style="font-size: 58px;">
    <carbon:screen />
  </div>

  <div class="text-4xl font-bold text-emerald-400 mb-3">
    Los hace visibles
  </div>

  <div class="text-2xl leading-relaxed text-white">
    Los presenta en pantallas, en el sitio web y mediante APIs para otras aplicaciones.
  </div>
</div>

</div>
</div>
---
layout: default
title: ¿Qué muestra Infobús?
---

<div class="h-full flex flex-col justify-center gap-4 text-3xl leading-relaxed">

<v-clicks>

- **Horarios y rutas** del bus interno
- **Ubicación de los buses** en tiempo real
- **Ocupación de asientos**
- **Alertas y actualizaciones** de los viajes
- **Estado de los viajes activos**

</v-clicks>

</div>
---
layout: default
kicker: ¿Quién hace qué?
title: Databús e Infobús
---

<div
  class="w-full flex items-stretch justify-center gap-6"
  style="transform: translateY(55px);"
>

<div
  class="p-8 rounded-xl border border-orange-500/40 bg-white/5"
  style="width: 460px; min-height: 220px; flex-shrink: 0;"
>
  <div class="text-4xl font-bold text-orange-400 mb-5">
    Databús — genera los datos
  </div>

  <div class="text-3xl leading-relaxed text-white">
    Produce los feeds GTFS: horarios y tiempo real.
  </div>
</div>

<div
  class="p-8 rounded-xl border border-blue-400/40 bg-white/5"
  style="width: 460px; min-height: 220px; flex-shrink: 0;"
>
  <div class="text-4xl font-bold text-blue-400 mb-5">
    Infobús — publica para usuarios
  </div>

  <div class="text-3xl leading-relaxed text-white">
    Los muestra en vivo a las personas usuarias.
  </div>
</div>

</div>

---
layout: default
kicker: ¿Cómo llega a las personas?
title: Tres canales
---

<div
  class="w-full flex items-stretch justify-center gap-5"
  style="transform: translateY(55px);"
>

<div
  class="p-8 rounded-xl border border-orange-500/40 bg-white/5"
  style="width: 340px; min-height: 210px; flex-shrink: 0;"
>
  <div class="text-6xl text-orange-400 mb-5">
    <lucide:tv />
  </div>

  <div class="text-4xl font-bold text-orange-400 mb-4">
    Pantallas
  </div>

  <div class="text-2xl leading-relaxed text-white">
    En las paradas de autobús.
  </div>
</div>

<div
  class="p-8 rounded-xl border border-blue-400/40 bg-white/5"
  style="width: 340px; min-height: 210px; flex-shrink: 0;"
>
  <div class="text-6xl text-blue-400 mb-5">
    <lucide:globe />
  </div>

  <div class="text-4xl font-bold text-blue-400 mb-4">
    Sitio web
  </div>

  <div class="text-2xl leading-relaxed text-white">
    Consulta desde cualquier dispositivo.
  </div>
</div>

<div
  class="p-8 rounded-xl border border-emerald-400/40 bg-white/5"
  style="width: 340px; min-height: 210px; flex-shrink: 0;"
>
  <div class="text-6xl text-emerald-400 mb-5">
    <lucide:plug />
  </div>

  <div class="text-4xl font-bold text-emerald-400 mb-4">
    APIs
  </div>

  <div class="text-2xl leading-relaxed text-white">
    Integración con otros sistemas.
  </div>
</div>

</div>
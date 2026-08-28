# Plan de Trabajo Vaqueros

Experiencia web del plan de trabajo 2026-2027 del Club Voleibol Vaqueros de Bayamón — equipos 15 Carlos y 16 Carlos.

## Contenido

Sitio de una sola página, 20 capítulos a pantalla completa, con switch entre los equipos 15U y 16U: bienvenida, metodología internacional, roster, cultura del entrenador, psicología deportiva, preparación física, Voleii, MOVE 5ª fase, periodos, macrociclo, calendario de torneos, cierre de temporada, inscripciones, uniformes, costos y reglas.

## Deploy

`deploy/index.html` es un archivo estático autocontenido — no requiere build, dependencias ni servidor.

En Vercel:

- Framework preset: **Other**
- Root Directory: **deploy**
- Build Command: *(vacío)*
- Output Directory: *(vacío)*

Cada push a la rama de producción redespliega automáticamente.

## Editar

La fuente es `Plan de Trabajo Vaqueros.dc.html` en la raíz. Después de editarla hay que regenerar `deploy/index.html`.

---

Entrenador: Carlos Torres · catd04@gmail.com · 787-379-5861

# Sistemas de Gestión — Proyecto Integrador

Contexto compartido para Claude Code. Este archivo se commitea al repo, así
cualquier integrante del equipo arranca con la misma base.

## Qué es este repo

Materia **Sistemas de Gestión**, 5° año de Ingeniería en Sistemas de Información,
UTN Facultad Regional San Rafael, ciclo lectivo 2026. Profesor: Juan Gijón.

Equipo:
- Lepez Joaquín
- Geyer Juan José
- Lopez Juan
- Sorato Emiliano

El repo contiene el material de cursada (PDFs de teoría y presentaciones por
clase) y las entregas del equipo (prácticas, TPs, actividades y el Proyecto
Integrador final).

## Proyecto Integrador

Caso provisto por la cátedra: **Implementación de un Sistema Integral de Gestión
Comercial y Tablero de Control** para una PyME comercial. Las consignas,
plantilla orientativa de entrega y criterios de evaluación están en
[Proyecto Integrador/](Proyecto%20Integrador/).

Antes de trabajar sobre el integrador, leer:
- `Práctica Integradora Guiada con caso provisto por la cátedra.pdf`
- `ISI5t0Sg2026_ Plantilla orientativa de entrega del proyecto integrador.pdf`
- `ISI5t0Sg2026_ Criterios generales de evaluación del proyecto.pdf`

## Estructura del repo

```
Unidad 1 - Identificación y preparación de proyectos/
Unidad 2 - Elementos Financieros, Contables y Económicos/
Unidad 3 - Formulación de Proyectos de Inversión/
Unidad 4 - Evaluación de Proyectos de Inversión/
Unidad 5 -    (Financiamiento y Análisis de Riesgo)
Unidad 6 y 7 - (Comunicación, Negociación y Toma de Decisiones)
Proyecto Integrador/
```

Convenciones que ya están en uso (respetarlas, no renombrar):
- Carpetas en español, con espacios, prefijo `Unidad N - ...`.
- Dentro de cada unidad: subcarpetas `CLASE N - <tema>` con los PDFs del
  profesor (`UTN-SdG-Clase_N-...pdf`) y subcarpetas tipo `PRACTICA`,
  `ACTIVIDAD`, `Actividades` para entregas del equipo.
- Las resoluciones del equipo se nombran `Resuelto - <consigna original>.pdf`
  o similar (ver ejemplo en `Unidad 5 -/Actividad/`).

## Cómo trabajar en este repo

- **Idioma**: todo en español (commits, comentarios, documentos, nombres de
  archivos de entrega).
- **No tocar el material del profesor** (PDFs `UTN-SdG-Clase_*`). Si hay que
  anotar sobre un PDF, crear una copia con sufijo `-anotado` o un archivo
  aparte.
- **Entregas del equipo**: ubicarlas dentro de la unidad correspondiente, en
  la subcarpeta de práctica/actividad que ya existe.
- **Antes de crear una carpeta nueva**: revisar si ya hay una equivalente.
  Preferir agregar a la estructura existente antes que inventar otra paralela.

## Reglas obligatorias para Claude Code (acordadas por el equipo)

Estas condiciones aplican siempre que se trabaje sobre este repo, en cualquier
sesión y para cualquier integrante del equipo:

1. **Mantener este `CLAUDE.md` siempre actualizado.** Apenas surja una
   decisión, convención, preferencia del equipo o contexto nuevo de la
   cursada que valga la pena recordar para futuras sesiones, agregarlo o
   actualizarlo en este archivo en el mismo turno. No esperar al final de
   la sesión ni a que el usuario lo pida explícitamente.
2. **Commit + push por cada punto que se va terminando.** No batchear
   entregas en un único commit gigante al final. Cada vez que se completa
   un punto concreto (una consigna resuelta, una sección redactada, una
   actualización a `CLAUDE.md`, etc.), hacer commit con mensaje descriptivo
   en español y `git push origin main` enseguida, para que el resto del
   equipo lo vea sin demora.
   - Excepción: si el push falla por permisos o por trabajo sin terminar a
     medio camino, avisar al usuario antes de seguir.

## Convenciones de git

- Commits en español, prefijos `feat:`, `fix:`, `docs:`, `chore:`.
  Ej: `docs: agrega resolución TP2 Unidad 2`.
- No commitear:
  - Archivos temporales de Office (ya cubierto por `.gitignore`: `~$*`).
  - `desktop.ini`, `Thumbs.db`, `.DS_Store` (ya en `.gitignore`).
  - `.claude/settings.local.json` (configuración local de Claude Code, ya en
    `.gitignore`).
  - Archivos de crash de bash en Windows (`bash.exe.stackdump`) — si aparecen
    nuevos, no commitearlos.
- PRs / merges: coordinar por el grupo del equipo antes de mergear cambios
  grandes a `main`.

## Cosas que Claude Code puede ayudar a hacer acá

- Resumir / explicar el contenido de un PDF de teoría.
- Armar borradores de las consignas (TPs, actividades, entregas) en
  Markdown o plantillas para luego pasar a Word/PDF.
- Estructurar el Proyecto Integrador siguiendo la plantilla orientativa de
  la cátedra.
- Cálculos financieros típicos de la materia: VAN, TIR, payback, flujo de
  fondos, CAPM, WACC, simulación Monte Carlo, tablas de amortización.

## Cosas a evitar

- Renombrar masivamente carpetas/archivos del profesor — rompe los links que
  el equipo tiene en sus máquinas y en notas externas.
- Convertir PDFs del profesor a otros formatos y borrar el original.
- Generar entregas finales sin revisar los criterios de evaluación de la
  cátedra (`ISI5t0Sg2026_ Criterios generales de evaluación del proyecto.pdf`).

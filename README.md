# Turbo Racing Lab 🏁

Garage digital para proyectos de Turbo Racing México / Vic's Pulse Timing.

## Objetivo

Centralizar, versionar y publicar:

- Spotters inteligentes
- Raceboards
- Overlays OBS
- Dashboards HTML
- Reportes de carrera
- Tablas de puntos
- Fichas de pilotos
- Assets oficiales
- Documentación técnica

## Estructura

```text
/assets
  /logos
  /tracks
  /images

/apps
  /spotter
  /raceboard
  /overlays
  /dashboards
  /reports

/data
  /csv
  /json
  /samples

/docs
  README_TECNICO.md
  VERSIONADO.md
  CHANGELOG.md
```

## Reglas base

- Mantener versiones visibles en UI y nombre de archivo.
- No romper funciones estables sin documentar el cambio.
- Usar nombres cortos y claros.
- Separar assets, datos y apps.
- Todo cambio importante debe registrarse en `CHANGELOG.md`.
- En narrativa de carrera, priorizar vueltas/tiempo antes que solo tiempo.

## Convención sugerida

```text
nombre_proyecto_vX.Y.Z.W.html
```

Ejemplos:

```text
vics_Smart_Spotter_v0.6.2.3.html
Vics_live_metrics_TRM_v0.0.0.17.html
Vics_Smart_Raceboard_v3.0.1.89.html
```

## Estado

Repositorio inicial preparado para trabajar proyectos HTML de Turbo Racing México.

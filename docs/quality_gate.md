# Quality gate

## Estado general del sistema

El sistema esta en estado apto para carga de datos reales, pero todavia no esta listo para generar un CV ATS v1 final. La estructura base es clara, versionable y separa correctamente:

- Perfil estructurado en `profile/`.
- CV maestro en `cv_master/`.
- Keywords y riesgos ATS en `keywords/`.
- Plantillas en `templates/`.
- Documentacion operativa en `docs/`.

No se detectaron archivos privados crudos listados por Git en `input/` u `outputs/` durante la revision.

## Archivos revisados

### JSON

- `profile/profile.master.json`
- `profile/identity.json`
- `profile/experience.json`
- `profile/education.json`
- `profile/skills.json`
- `profile/projects.json`
- `profile/achievements.json`
- `profile/languages.json`
- `profile/preferences.json`

Resultado: todos los JSON son validos.

### Markdown

- `README.md`
- `cv_master/*.md`
- `templates/*.md`
- `docs/*.md`

Resultado: estructura clara, con titulos consistentes y TODOs visibles.

### YAML

- `keywords/keywords.master.yaml`
- `keywords/maintenance.yaml`
- `keywords/mining.yaml`
- `keywords/oil_gas.yaml`
- `keywords/fleet.yaml`
- `keywords/planner.yaml`
- `keywords/reliability.yaml`
- `keywords/cmms.yaml`
- `keywords/industrial_saas.yaml`
- `keywords/red_flags.yaml`

Resultado: archivos legibles y organizados por categoria. No se detectaron duplicados graves. Hay repeticion intencional de keywords entre el master y archivos por categoria.

## Riesgos detectados

- El perfil todavia no tiene metricas verificadas: OTs mensuales, equipos gestionados, tiempos, volumen de repuestos o mejoras.
- `SAP/ERP` esta declarado de forma generica. No hay evidencia para declarar un modulo especifico.
- `RCA` y `root cause analysis` aparecen como keywords tecnicas en reliability, pero el archivo ya aclara que no estan explicitamente comprobadas.
- `oil & gas` aparece como vertical objetivo. No debe presentarse como experiencia directa sin evidencia.
- La app de gestion de mantenimiento esta mencionada, pero falta estado real, alcance y nombre. Si el nombre es Garage365, debe confirmarse antes de usarlo.
- La experiencia independiente tiene un periodo futuro/actual desde `Jul 2025 - Actualidad` segun el CV extraido; conviene validar consistencia cronologica antes de generar versiones finales.

## Inconsistencias

- `profile.master.json` incluye TODOs por experiencia; `profile/experience.json` no replica esos TODOs.
- `profile.master.json` usa `equipos de perforacion`; `profile/skills.json` usa `perforacion`. No es contradictorio, pero conviene normalizar.
- `profile.master.json` dice `Participacion en auditorias...`; `profile/experience.json` dice `Participacion activa...`. No contradice el CV, pero conviene usar una sola redaccion.
- `profile.master.json` incluye `professional` dentro de skills; `profile/skills.json` no incluye esa categoria.
- `profile.master.json` incluye `target_roles`; no existe un archivo separado `target_roles.json`. No es obligatorio, pero podria ayudar en la siguiente etapa.

## Datos faltantes criticos

- TODO: cantidad de equipos gestionados.
- TODO: OTs mensuales.
- TODO: tipos/modelos de equipos.
- TODO: sistemas usados para OTs, repuestos, reportes y trazabilidad.
- TODO: reportes creados y frecuencia.
- TODO: repuestos/materiales controlados.
- TODO: proveedores o servicios externos coordinados.
- TODO: mejoras logradas con evidencia.
- TODO: tiempos antes/despues.
- TODO: funciones reales en SAP/ERP.
- TODO: funciones reales en Excel/VBA.
- TODO: estado real de Garage365 o de la app de gestion de mantenimiento.
- TODO: industrias objetivo.
- TODO: roles objetivo priorizados.
- TODO: disponibilidad.
- TODO: pretension salarial.
- TODO: nivel real de ingles.

## Recomendaciones antes de generar CV ATS

1. Completar `docs/data_intake.md` con datos reales y verificables.
2. Definir 2 o 3 roles prioritarios usando `docs/role_priority_matrix.md`.
3. Confirmar herramientas exactas: SAP/ERP, CMMS, Excel, VBA, Power BI.
4. Normalizar pequenas diferencias entre `profile.master.json` y archivos separados.
5. Crear una primera oferta laboral de prueba en `job_posts/raw/`.
6. Generar un CV ATS v1 solo despues de resolver los TODOs criticos o dejarlos marcados de forma explicita.

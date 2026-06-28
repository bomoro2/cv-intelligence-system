# CV Intelligence System - Bonifacio Morales

Base maestra reutilizable para generar CVs adaptados a ofertas laborales, cover letters, respuestas para ATS/formularios, LinkedIn, elevator pitch y versiones PDF/DOCX/HTML.

## Objetivo

Mantener una fuente unica, versionable y verificable del perfil profesional de Bonifacio Morales. El sistema esta pensado para:

- Centralizar datos del CV en Markdown, JSON y YAML.
- Adaptar el contenido a roles de mantenimiento, planificacion, repuestos, mineria, oil & gas, fleet management, reliability, CMMS y SaaS industrial.
- Evitar datos inventados, lenguaje inflado o metricas no comprobadas.
- Marcar como TODO cualquier dato faltante o pendiente de validacion.

## Fuentes

- CV actual: `input/CV_Bonifacio_Morales.pdf`
- Perfil estructurado: `profile/profile.master.json`
- CV maestro editable: `cv_master/`
- Keywords por vertical: `keywords/`
- Plantillas reutilizables: `templates/`

## Flujo de uso recomendado

1. Guardar una oferta laboral en `job_posts/raw/`.
2. Extraer requisitos y keywords en `job_posts/parsed/`.
3. Comparar la oferta contra `profile/profile.master.json` y `keywords/`.
4. Crear una version adaptada usando `templates/cv_ats.md`, `templates/cover_letter.md` o la plantilla que corresponda.
5. Guardar resultados en `outputs/` segun formato o canal.

## Reglas editoriales

- Usar espanol profesional y tecnico.
- Incluir keywords en ingles cuando sean terminos tecnicos habituales.
- No inventar metricas, certificaciones, sistemas ni responsabilidades.
- No usar "SAP PM" salvo que haya evidencia especifica.
- Marcar pendientes con `TODO:`.
- Priorizar claridad ATS: titulos simples, keywords verificables, bullets concretos.

## Estado inicial

Contenido cargado desde el PDF actual. La extraccion automatica fue posible, con normalizacion manual de acentos y caracteres.


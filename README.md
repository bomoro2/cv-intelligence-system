# CV Intelligence System - Bonifacio Morales

Base maestra reutilizable para generar CVs adaptados a ofertas laborales, cover letters, respuestas para ATS/formularios, LinkedIn, elevator pitch y versiones PDF/DOCX/HTML.

## Proposito del proyecto

Mantener una fuente unica, versionable y verificable del perfil profesional de Bonifacio Morales. El sistema esta pensado para:

- Centralizar datos del CV en Markdown, JSON y YAML.
- Adaptar el contenido a roles de mantenimiento, planificacion, repuestos, mineria, oil & gas, fleet management, reliability, CMMS y SaaS industrial.
- Evitar datos inventados, lenguaje inflado o metricas no comprobadas.
- Marcar como TODO cualquier dato faltante o pendiente de validacion.

## Estructura del repo

- `input/`: fuentes privadas locales. No versionar PDFs/DOCX originales.
- `profile/`: perfil estructurado en JSON.
- `cv_master/`: contenido maestro editable del CV en Markdown.
- `keywords/`: keywords y riesgos por categoria.
- `templates/`: plantillas para CV, cover letter, LinkedIn y formularios.
- `job_posts/`: ofertas laborales crudas, parseadas y evaluadas.
- `outputs/`: CVs y documentos generados. No versionar.
- `docs/`: documentacion del sistema, privacidad y flujo de trabajo.

## Advertencia de privacidad

Este repositorio contiene datos personales y estrategia laboral. Debe mantenerse privado. No subir al repositorio archivos crudos como PDFs originales, DOCX originales, `.env`, secretos, exports de plataformas laborales ni documentos generados con datos sensibles.

## Flujo de uso recomendado

1. Guardar una oferta laboral en `job_posts/raw/`.
2. Extraer requisitos y keywords en `job_posts/parsed/`.
3. Comparar la oferta contra `profile/profile.master.json` y `keywords/`.
4. Crear una version adaptada usando `templates/cv_ats.md`, `templates/cover_letter.md` o la plantilla que corresponda.
5. Guardar resultados en `outputs/` segun formato o canal.

## Estado actual

- Base maestra creada en Markdown, JSON y YAML.
- Contenido inicial cargado desde el CV actual.
- TODOs marcados donde faltan metricas, sistemas exactos o evidencia.
- Reglas basicas de privacidad agregadas en `.gitignore`.
- Normalizacion de line endings agregada en `.gitattributes`.

## Proximos pasos

- Revisar y completar TODOs con datos reales.
- Confirmar sistemas exactos usados en SAP/ERP/CMMS.
- Definir roles e industrias prioritarias.
- Agregar ofertas laborales de prueba en `job_posts/raw/`.
- Generar primeras versiones adaptadas solo cuando el contenido base este validado.

## Reglas editoriales

- Usar espanol profesional y tecnico.
- Incluir keywords en ingles cuando sean terminos tecnicos habituales.
- No inventar metricas, certificaciones, sistemas ni responsabilidades.
- No usar "SAP PM" salvo que haya evidencia especifica.
- Marcar pendientes con `TODO:`.
- Priorizar claridad ATS: titulos simples, keywords verificables, bullets concretos.

## Estado inicial

Contenido cargado desde el PDF actual. La extraccion automatica fue posible, con normalizacion manual de acentos y caracteres.

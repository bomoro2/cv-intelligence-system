# Roadmap

## Fase 1: CV Maestro

- Centralizar experiencia, habilidades, proyectos, educacion e idiomas en `cv_master/`.
- Mantener TODOs para metricas y datos pendientes.
- Separar contenido ATS de contenido visual.

## Fase 2: Perfil JSON

- Mantener `profile/profile.master.json` como fuente estructurada.
- Sincronizar archivos JSON separados por dominio.
- Agregar evidencia y TODOs por cada dato sensible.

## Fase 3: Motor ATS

- Crear parser simple de ofertas en `job_posts/parsed/`.
- Comparar keywords contra `keywords/`.
- Usar `docs/scoring_method.md` como score propio interno.

## Fase 4: Generador automatico

- Generar CV adaptado, cover letter, LinkedIn, Gupy, Workday y elevator pitch desde plantillas.
- Guardar versiones en `outputs/`.
- Mantener historial por oferta.

## Fase 5: Agente IA de candidatura

- Leer oferta.
- Evaluar match y riesgos.
- Proponer CV y respuestas.
- Marcar gaps antes de enviar.
- Preparar argumentos para entrevista.


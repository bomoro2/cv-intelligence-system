# Politica de privacidad y datos

## Que datos contiene el repo

Este repositorio contiene informacion profesional y personal de Bonifacio Morales Romero, incluyendo:

- Identidad profesional y datos de contacto estructurados.
- Experiencia laboral, educacion, habilidades, proyectos e idiomas.
- Keywords por industria y rol objetivo.
- Plantillas para CVs, cover letters, LinkedIn y formularios laborales.
- Estrategia de candidatura y reglas editoriales.

## Por que debe ser privado

El repositorio debe mantenerse privado porque combina datos personales, historial laboral, estrategia de busqueda, respuestas base para plataformas y posibles versiones adaptadas a ofertas especificas.

Aunque el contenido este orientado a postulaciones, no todo debe ser publico ni indexable. La exposicion accidental podria revelar datos de contacto, preferencias laborales, empresas objetivo, documentos generados o informacion sensible de procesos de seleccion.

## Archivos que no deben subirse

No versionar:

- `input/*.pdf`
- `input/*.docx`
- `outputs/`
- PDFs generados.
- DOCX generados.
- HTMLs generados con datos personales.
- `.env`
- `.env.*`
- `secrets/`
- Exports crudos de portales laborales.
- Capturas, cartas o documentos que incluyan datos privados de terceros.

## Como manejar CVs generados

- Guardar versiones generadas localmente en `outputs/`.
- No commitear versiones PDF/DOCX/HTML.
- Si una version adaptada necesita conservarse, guardar solo una representacion Markdown sanitizada y sin datos sensibles adicionales.
- No incluir informacion de empresas, reclutadores o procesos privados salvo que sea necesario y seguro.
- Eliminar versiones obsoletas cuando ya no sean utiles.

## Regla general

Si un archivo contiene datos personales crudos, documentos finales enviados, secretos, informacion de terceros o evidencia privada, debe permanecer fuera de Git.


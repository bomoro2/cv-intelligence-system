# Flujo de trabajo del repositorio

## Ramas recomendadas

- `main`: version estable y revisada de la base maestra.
- `profile/update-*`: cambios en perfil, experiencia, skills o TODOs.
- `job-post/*`: trabajo sobre una oferta laboral especifica.
- `docs/*`: documentacion, reglas, privacidad o procesos.
- `templates/*`: cambios en plantillas.

## Uso de main

Mantener `main` limpio. Solo deberia recibir cambios revisados, sin PDFs, DOCX, HTML generados, secretos ni archivos crudos privados.

## Commits chicos

Hacer commits pequenos y faciles de revisar. Un commit deberia cubrir una idea concreta:

- Actualizar README.
- Agregar politica de privacidad.
- Ajustar keywords de mantenimiento.
- Completar TODOs validados.
- Agregar plantilla nueva.

## Convencion de commits

Formato recomendado:

```text
tipo: descripcion breve
```

Tipos sugeridos:

- `docs`: documentacion.
- `profile`: cambios en datos estructurados del perfil.
- `cv`: cambios en CV maestro.
- `keywords`: cambios en keywords o red flags.
- `templates`: cambios en plantillas.
- `workflow`: cambios de proceso o higiene del repo.

Ejemplos:

```text
workflow: agregar gitignore y gitattributes
docs: agregar politica de privacidad
cv: completar experiencia de mantenimiento validada
keywords: ajustar terminos de CMMS
```

## Flujo para agregar una oferta laboral

1. Crear un archivo en `job_posts/raw/` con el texto original de la oferta.
2. Crear una version parseada en `job_posts/parsed/` con requisitos, responsabilidades, herramientas y keywords.
3. Comparar contra `profile/profile.master.json` y `keywords/`.
4. Registrar gaps como TODO, sin inventar experiencia.
5. Guardar evaluacion interna en `job_posts/scored/` si corresponde.

## Flujo para generar una version de CV

1. Elegir la plantilla adecuada en `templates/`.
2. Usar datos de `profile/profile.master.json` y `cv_master/`.
3. Adaptar keywords solo si estan respaldadas por experiencia real.
4. Marcar informacion faltante con TODO.
5. Guardar archivos generados en `outputs/`.
6. No commitear PDFs, DOCX, HTML ni documentos finales con datos sensibles.

## Antes de cada commit

- Revisar que no haya archivos privados crudos staged.
- Confirmar que `input/*.pdf`, `input/*.docx` y `outputs/` sigan ignorados.
- Revisar que los cambios no inventen metricas ni herramientas.
- Confirmar que el README y docs reflejen el flujo actual.


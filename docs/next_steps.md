# Proximos pasos hacia el primer CV ATS v1

## Objetivo

Llegar a una primera version ATS clara, tecnica y verificable, sin inflar el perfil ni inventar metricas.

## Plan exacto

1. Completar `docs/data_intake.md`
   - Priorizar OTs mensuales, equipos gestionados, sistemas usados, reportes, repuestos y proveedores.
   - Dejar TODO donde no haya dato seguro.

2. Definir roles prioritarios
   - Usar `docs/role_priority_matrix.md`.
   - Elegir maximo 2 o 3 roles para la primera version.
   - Recomendacion inicial: Maintenance Planner, Oficina Tecnica y Material Controller.

3. Normalizar perfil estructurado
   - Revisar diferencias menores entre `profile.master.json` y archivos separados.
   - Mantener el master como fuente principal.
   - No agregar datos sin evidencia.

4. Preparar primera oferta de prueba
   - Guardar texto en `job_posts/raw/`.
   - Parsear requisitos en `job_posts/parsed/`.
   - Marcar keywords verificables y brechas.

5. Evaluar match con score propio
   - Usar `docs/scoring_method.md`.
   - Separar hechos comprobados, hipotesis y TODOs.
   - No tratar el score como resultado real de ATS.

6. Crear borrador ATS v1 en Markdown
   - Usar `templates/cv_ats.md`.
   - Guardar el borrador como Markdown antes de generar cualquier PDF/DOCX/HTML.
   - Mantener bullets tecnicos, claros y verificables.

7. Revisar riesgos antes de exportar
   - Confirmar que no declare modulos SAP especificos sin evidencia.
   - Confirmar que no use metricas inventadas.
   - Confirmar que oil & gas aparezca solo como objetivo o transferencia si no hay experiencia directa.
   - Confirmar que Garage365/app tenga estado real validado.

## Criterio de salida para CV ATS v1

- Perfil con rol objetivo definido.
- Experiencia priorizada para el rol.
- Keywords verificables incluidas.
- Brechas marcadas como TODO.
- Sin archivos generados en `outputs/` hasta aprobacion.
- Sin datos privados crudos versionados.

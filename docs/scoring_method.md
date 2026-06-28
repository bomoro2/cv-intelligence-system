# Metodo de scoring propio

Este sistema usa un score interno para priorizar adaptaciones de CV. No representa un score real de ATS ni promete resultados en plataformas externas.

## Score total sugerido: 100 puntos

- **Match de cargo objetivo (20 pts):** coincidencia entre la oferta y roles objetivo del perfil.
- **Keywords verificables (25 pts):** presencia de terminos de la oferta que tambien esten respaldados por experiencia, skills o proyectos.
- **Experiencia relevante (25 pts):** cercania entre responsabilidades reales y requisitos del puesto.
- **Herramientas y sistemas (15 pts):** match con SAP/ERP, Excel, VBA, Power BI, CMMS u otras herramientas solicitadas.
- **Riesgo ATS/editorial (15 pts):** penaliza exageraciones, metricas inventadas, terminos no comprobados o estructura dificil de parsear.

## Penalizaciones

- -20 pts: declarar herramienta o modulo no comprobado.
- -15 pts: declarar industria directa sin respaldo.
- -10 pts: usar metricas no verificadas.
- -10 pts: CV con formato dificil de leer por ATS.
- -5 pts: omitir keywords importantes que si estan respaldadas por el perfil.

## Uso

1. Leer la oferta.
2. Extraer requisitos obligatorios, deseables y keywords.
3. Comparar con `profile/profile.master.json`.
4. Marcar gaps como TODO.
5. Generar una version adaptada sin inventar datos.

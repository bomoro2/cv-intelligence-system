# Matriz inicial de prioridad por rol

Compatibilidad estimada con base en el CV actual y los archivos del sistema. No representa un score ATS real.

| Rol | Compatibilidad actual estimada | Keywords principales | Brechas | Datos que hacen falta | Prioridad recomendada |
| --- | --- | --- | --- | --- | --- |
| Maintenance Planner | Alta | maintenance planning, OTs, preventivos, correctivos, paradas, materiales, servicios externos | Faltan metricas y herramientas exactas de planificacion | TODO: OTs mensuales, equipos gestionados, sistema usado, alcance semanal/mensual | Alta |
| Oficina Tecnica | Alta | reportes, trazabilidad, SAP/ERP, Excel avanzado, VBA, auditorias operativas, mantenimiento | Falta precisar reportes, procesos y responsabilidades documentales | TODO: reportes creados, frecuencia, destinatarios, funciones reales en SAP/ERP y Excel/VBA | Alta |
| Fleet Coordinator | Media | fleet management, vehiculos livianos, camionetas, tractores, maquinaria, diagnostico, reparacion | Experiencia de taller comprobada, pero falta coordinacion formal de flota | TODO: cantidad de unidades, tipo de flota, clientes, planificacion de mantenimiento vehicular | Media |
| Material Controller | Media-Alta | repuestos, spare parts, stock, materiales criticos, proveedores, trazabilidad, envios a proyecto | Falta volumen, criticidad y alcance de control | TODO: repuestos/materiales controlados, proveedores, servicios externos, sistema de stock | Alta |
| Reliability Assistant | Media | analisis de fallas, fallas recurrentes, reportes de mantenimiento, confiabilidad | RCA formal no esta comprobado; faltan ejemplos de fallas | TODO: confirmar RCA, ejemplos, causas, acciones, resultados | Media |
| CMMS Consultant | Media | CMMS, work orders, OTs, avisos, preventivos, correctivos, SAP/ERP, trazabilidad | Experiencia como usuario esta sugerida; falta experiencia consultiva o implementacion | TODO: sistema exacto, funciones usadas, configuracion, capacitacion, soporte a usuarios | Media |
| Customer Success Industrial | Media | mantenimiento industrial, soporte tecnico, SaaS industrial, reportes, app de mantenimiento | Falta experiencia directa en clientes SaaS, onboarding o gestion de cuentas | TODO: trato con usuarios/clientes, demos, soporte, documentacion, experiencia comercial | Media-Baja |
| SaaS Industrial | Media | industrial SaaS, software de mantenimiento, app de gestion, Flutter, Dart, Swift, OTs, stock | Proyecto existe como desarrollo personal, pero falta estado real y alcance tecnico | TODO: estado de Garage365/app, funcionalidades implementadas, usuarios, arquitectura | Media |

## Lectura recomendada

- Prioridad inmediata: `Maintenance Planner`, `Oficina Tecnica`, `Material Controller`.
- Prioridad secundaria: `Fleet Coordinator`, `Reliability Assistant`, `CMMS Consultant`.
- Prioridad exploratoria: `Customer Success Industrial`, `SaaS Industrial`.

## Reglas de uso

- No presentar hipotesis como hechos.
- No declarar SAP PM sin evidencia.
- No declarar RCA formal sin confirmacion.
- No declarar experiencia directa en SaaS industrial si solo existe proyecto personal.
- Usar TODO cuando falten datos.


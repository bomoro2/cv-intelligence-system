# Formulario de carga de datos reales

Snapshot de carga: 2026-06-28.

Completar solo con informacion real y verificable. Si un dato no esta claro, dejar `TODO:` y no inventar.

## Identidad y privacidad

- CV principal: espanol.
- Base futura: ingles.
- Telefono/email: ocultar en versiones publicas.
- LinkedIn: existe, pendiente de mejora.
- GitHub de Garage365: privado; no mostrar por ahora.
- Empresa actual: puede mostrarse en CV privado. En versiones publicas usar "empresa de servicios de perforacion / mantenimiento industrial".
- Garage365: no nombrar clientes.
- No incluir datos sensibles internos, nombres de personas ni links privados.

## Objetivo laboral

- Busqueda abierta: Argentina, internacional y remoto.
- Modalidad: abierto a relacion de dependencia.
- Objetivo doble: empleo bien pago y crecimiento de Garage365.
- Roles objetivo:
  - Maintenance Planner / Planificador de Mantenimiento.
  - Oficina Tecnica de Mantenimiento.
  - Material Controller / Repuestos / Abastecimiento tecnico.
  - Supervisor de Mantenimiento.
  - CMMS Consultant.
  - Customer Success Industrial.
  - SaaS Industrial / Software industrial.
- Industrias objetivo:
  - Mantenimiento industrial.
  - Perforacion.
  - Flotas.
  - Talleres.
  - Mineria como industria objetivo.
  - SaaS industrial.
  - Digitalizacion de operaciones.
- Disponibilidad:
  - Viajes.
  - Campo.
  - Roster.
  - Proyectos remotos.
  - Mineria.
  - Mudanza si el lugar es tranquilo/familiar.
- Pretension salarial:
  - Piso deseado: ARS 2.500.000 mensuales.
  - Objetivo ideal: ARS 3.500.000 mensuales.
  - No incluir pretension salarial en CV. Guardar solo en `profile/preferences.json`.

## Licencias

- A1.2: motos.
- B1: autos y camionetas.

## Datos operativos de mantenimiento

- Cantidad de equipos gestionados:
  - Respuesta: aprox. 150 equipos propios bajo gestion directa de informacion.
  - Relacion adicional: aprox. 20 equipos alquilados actuales.
  - Vision indirecta: aprox. 80 camionetas y aprox. 40 camiones gestionados por companeros.

- OTs mensuales:
  - Respuesta: aprox. 760 tareas/OTs mensuales como estimacion conservadora.
  - Calculo: proyecto 6 mecanicos activos x 2 tareas/dia x 30 dias = aprox. 360 tareas/mes; base 10 mecanicos x 2 tareas/dia x 20 dias = aprox. 400 tareas/mes.

- Entorno operativo:
  - 6 proyectos activos.
  - Proyecto: 6 mecanicos activos + 6 de descanso, aprox. 12 en rotacion.
  - Base: aprox. 10 mecanicos fijos.

- Tipos de equipos:
  - Perforadoras diamantinas.
  - Perforadoras rotary.
  - Bombas de lodo.
  - Generadores.
  - Torres de iluminacion.
  - Compresores.
  - Boosters.
  - Equipos mas criticos: perforadoras y generadores.
  - Equipos que mas generan OTs: perforadoras y generadores.

- Tipo de mantenimiento predominante:
  - Base: mayor volumen de correctivos.
  - Proyecto/campo: emergencias operativas y preventivos.

## Sistemas y datos

- Sistemas usados:
  - Sistema propio de la empresa para gestion de activos y mantenimiento.
  - No afirmar modulos SAP especificos sin evidencia.
  - Funciones: OTs, avisos, preventivos, correctivos, pedidos, stock, compras, historial, reportes, consulta y seguimiento de repuestos.

- Excel:
  - Herramienta maestra de control.
  - Manejo de datos exportados desde el sistema interno.
  - Limpieza, consolidacion, control y analisis de informacion operativa.

- Power Query:
  - Relacion de datos aislados exportados del sistema.
  - Transformacion, limpieza y consolidacion de datos.

- Tablas dinamicas:
  - Visualizacion de pendientes y estados.

- VBA:
  - Filtrado avanzado de requerimientos.
  - Control de inconsistencias.
  - Deteccion de repuestos marcados como no cumplidos cuando ya estaban cumplidos.

- Power BI:
  - Nivel basico/en practica.
  - No presentarlo como avanzado.

## Repuestos y materiales

- Base:
  - Consumibles.
  - Bulones.
  - Correas.
  - Retenes.
  - Repuestos correctivos segun condicion del equipo.

- Proyectos:
  - Filtros.
  - Insumos para mantenimientos preventivos.
  - Preventivos programados.

- Categorias:
  - Consumibles.
  - Filtros.
  - Aceites/lubricantes.
  - Correas.
  - Retenes.
  - Mangueras hidraulicas.
  - Bombas.
  - Motores.
  - Sensores.
  - Rodamientos.
  - Herramientas.
  - Repuestos criticos.

- Alcance:
  - Revision del pedido desde origen.
  - Cuestionamiento tecnico de lo solicitado.
  - Seguimiento hasta uso real en OT.
  - Validacion contra evidencia disponible.
  - Trazabilidad pedido -> compra -> entrega -> OT.
  - Coordinacion con compras.
  - Seguimiento y aceleracion de compras.
  - Resolucion de dudas tecnicas.
  - Busqueda y aprobacion de equivalencias.
  - Seguimiento de plazos de entrega.
  - Control constante de repuestos criticos.
  - Seguimiento de entregas/envios a proyecto.

- Volumen:
  - Aprox. 3000 lineas de pedido en los ultimos 6 meses.
  - Promedio aprox. 500 lineas de pedido mensuales.

## Reportes y analisis

- Pedidos pendientes / estado de requerimientos:
  - Proyectos: cada aprox. 15 dias.
  - Gerencia: semanal.
  - Control propio: diario.

- Tareas ejecutadas / control de horas operativas:
  - Frecuencia: dos veces al mes.
  - Objetivo: comparar tareas ejecutadas y horas operativas contra hora reloj, especialmente en base.

- Repuestos y tareas:
  - Cruce entre tareas ejecutadas, repuestos solicitados/usados y estado de pedidos.

- Horas de equipos / historicos:
  - Analisis de horas de uso por equipo.
  - Promedios de utilizacion.
  - Deteccion de cambios de uso para ajustar planificacion de servicios.

- Decisiones apoyadas por reportes:
  - Priorizacion diaria/semanal.
  - Seguimiento de pendientes.
  - Movimiento de compras/repuestos.
  - Ajustes de planificacion.
  - Reportes solicitados por gerencia.

## Planificacion preventiva

- Participacion actual: ajuste y seguimiento de planes preventivos existentes.
- Creacion puntual de plan preventivo para equipo nuevo/diferente: grua.
- Criterios:
  - Equipos: horas de operacion.
  - Vehiculos: kilometros.
- Periodicidad principal: servicios cada 300 horas.
- Deteccion:
  - Actualizacion diaria de horometros desde proyecto.
  - Carga de informacion en sistema.
  - Uso de semaforo de proximidad.
- Materiales:
  - Aviso de equipo proximo a servicio.
  - Materiales preventivos disponibles en proyecto por planificacion mensual.
- Ajuste por cambio de uso:
  - Si cambia el promedio de uso, se ajustan pedidos/materiales.
- Coordinacion:
  - Mecanico coordina con operaciones.
  - Intervencion propia si el preventivo se excede por mas de 24 horas.

## Fallas y correctivos

- Fallas recurrentes observadas:
  - Perforadoras: perdidas de aceite por mangueras rotas o sellos de pistones hidraulicos.
  - Generadores: fallas asociadas a motor.
  - Equipos electricos: fallas electricas intermitentes o de diagnostico complejo.

- Analisis:
  - Analisis propio de fallas ya resueltas para entender causa probable y acciones de mejora.
  - Deteccion de patrones por calidad de materiales, uso incorrecto o descuido operativo.
  - Propuesta de ideas de mejora ante fallas repetitivas.
  - No presentar como practica formal de confiabilidad si no existe evidencia.

- Control de OTs correctivas:
  - Revision de calidad de carga.
  - Solicitud de correccion y reenvio cuando la informacion esta incompleta o mal cargada.
  - Escalamiento a gerencia ante demoras importantes o falta de respuesta.
  - Consulta directa con mecanicos para comprender diagnosticos.
  - Seguimiento de equipos criticos parados hasta quedar operativos y sin novedades.

## Logros e impacto

- Problema inicial:
  - Carga y actualizacion de informacion excesivamente lenta.
  - Informacion dispersa o no disponible a tiempo.
  - Pedidos con errores, duplicados o innecesarios.
  - Riesgo de que preventivos pasen a gestion reactiva por falta de seguimiento.

- Mejoras:
  - Mejora de tiempos de actualizacion.
  - Mejor disponibilidad de informacion centralizada.
  - Reduccion de errores en pedidos/requerimientos.
  - Mayor control antes de derivar compras.
  - Mejor priorizacion diaria/semanal.
  - Optimizacion del tiempo propio: menos carga manual y mas analisis.

- Impacto estimado:
  - Antes podian pasar mas de 300 articulos mensuales a compras.
  - Actualmente pasan aprox. 50 articulos mensuales a compras.
  - El resto se gestiona internamente, ya esta planificado o disponible para retiro.
  - Se redujeron pedidos innecesarios/problematicos mediante validacion tecnica y control.
  - Equipos que antes podian permanecer cerca de 1 mes en taller ahora en muchos casos se resuelven en aprox. 1 semana, segun gravedad.
  - Gerencia solicito reporte de costos reales por servicio; se detecto variacion importante segun configuracion del equipo.

## Garage365 / G365

- Nombre: Garage365.
- Alias: G365.
- Estado:
  - Producto funcional.
  - Uso inicial en entorno real: una empresa lo utiliza para registrar eventos/tareas vinculadas a uno de sus clientes.
  - En expansion y mejora continua.
  - No nombrar clientes.
- Alcance actual:
  - Alta de equipos.
  - Checklists.
  - Ordenes de trabajo.
  - QR por equipo.
  - Sincronizacion con servidor.
  - Version mobile funcional.
  - Version desktop funcional.
  - Backend existente en desarrollo/despliegue.
- Tecnologias:
  - Flutter / Dart para mobile y desktop.
  - C# / .NET 8 para backend.
  - API web para sincronizacion.
  - Backend orientado a operacion con servidor.
  - TODO: confirmar si Render puede mencionarse como plataforma de despliegue.
- Problema que resuelve:
  - Reduce el acceso lento a informacion operativa.
  - Facilita el registro de eventos industriales desde el telefono.
  - Digitaliza tareas, checklists, OTs y trazabilidad de equipos.
  - No esta pensado solo para talleres.
  - Orientado a procesos industriales, mantenimiento, flotas, operaciones y servicios tecnicos.
- Posicionamiento:
  - Desarrollo personal.
  - Producto SaaS industrial funcional.
  - Herramienta de digitalizacion operativa.

## Experiencia en perforacion

- Tipo: pozos de agua.
- Equipos:
  - Plataforma de perforacion rotary.
  - Bombas de lodo asociadas.
  - Equipos auxiliares.
- Ubicacion/condiciones:
  - Cordillera.
  - Boca de pozo.
  - Turnos de 12 horas.
  - Esquema 20 dias arriba / 10 dias de descanso.
  - Condiciones operativas exigentes.
- Tareas:
  - Preparacion de fluidos de perforacion.
  - Limpieza de circuito de lodo.
  - Mantenimiento basico de bomba de lodo.
  - Control visual de maquina durante operacion.
  - Apoyo a mecanicos en reparaciones.
  - Operacion puntual de la maquina.
  - Identificacion de tipos de terreno durante perforacion.
  - Adaptacion operativa de maquina y fluidos segun terreno.
  - Comprension del proceso completo de perforacion de un pozo de agua.

## Taller propio / mecanica independiente

- Usar como respaldo tecnico salvo roles operativos.
- Equipos:
  - Motocicletas.
  - Autos.
  - Camionetas.
  - Camiones.
  - Tractores.
- Trabajos:
  - Diagnostico.
  - Motor.
  - Frenos.
  - Suspension.
  - Electricidad/electronica.
  - Hidraulica.
  - Mantenimiento general.
- Alcance:
  - Atencion a clientes cuando el trabajo ingresaba directamente.
  - Presupuestos.
  - Recomendacion/compra de repuestos.
  - Trabajo con ayuda en reparaciones mayores.
  - Trabajo individual en tareas livianas, electricidad/electronica y motos.
- Aprendizaje:
  - Importancia del registro tecnico.
  - Cuidado en diagnostico y reparacion.
  - Necesidad de informacion accesible para ejecutar trabajos correctamente.
  - Base conceptual que impulso Garage365.

## Encargado de operaciones - quebracho colorado

- Actividad inicial: compra y venta de postes de quebracho colorado.
- Expansion: propuso ampliar hacia servicios rurales y paso de venta de postes a proyectos completos.
- Responsabilidades:
  - Compra y venta.
  - Coordinacion con proveedores y clientes.
  - Gestion de camiones y permisos.
  - Logistica desde campo hasta destino final.
  - Viajes con mercaderia para conocer necesidades del cliente.
  - Adaptacion operativa segun tipo de cliente/proyecto.
  - Compra/coordinacion de materiales.
- Clientes:
  - Duenos de fincas.
  - Corralones.
  - Clientes particulares.
  - Productores rurales.
- Personal:
  - Contratacion eventual para carga de camiones.
  - Coordinacion de cuadrilla de aprox. 10 personas para alambrado.
- Proyectos:
  - Feedlots / corrales de cria de ganado.
  - Cargadores.
  - Mangas.
  - Toriles.
  - Cercado completo de fincas.
  - Renovacion de postes en alambrados existentes.
- Impacto:
  - Incremento de ventas de aprox. 1 camion mensual a aprox. 8 camiones mensuales.
  - Desarrollo de servicios/proyectos adicionales que elevaron fuertemente la facturacion.

## Educacion

- Tecnico en Sistemas Industriales.
- Universidad de Oriente, Puerto Ordaz, Venezuela.
- 2012-2016.
- Cursado academico completo.
- 2 materias pendientes para cierre formal del titulo.
- Redaccion recomendada: "Tecnico en Sistemas Industriales - cursado completo, 2 materias pendientes para titulacion formal."

## Certificaciones

- Sin certificaciones formales actuales.
- Roadmap recomendado:
  - Excel avanzado.
  - Power Query.
  - Power BI.
  - Maintenance Planning.
  - CMMS.
  - Confiabilidad basica.
  - Seguridad/HSE.
  - SAP/ERP basico si aplica.

## Idiomas

- Espanol nativo.
- Ingles tecnico: lectura de documentacion tecnica.
- Escritura limitada.
- No preparado actualmente para entrevista oral completa.
- No decir intermedio.

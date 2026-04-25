# Challenge de la Sesión 6

## Integrar el diseño completo de un agente de IA de atención a clientes

## Objetivo del challenge

Tomar decisiones finales para una primera versión operable del agente.

La idea es definir:
- qué configuración general tendrá el agente
- qué tradeoffs se aceptan
- qué condiciones deben cumplirse antes de lanzar
- cómo se operará y revisará el sistema

Todo esto editando archivos simples.

## Duración sugerida

15 a 25 minutos.

## Modalidad

- individual, o mejor
- en parejas o equipos de 3

## Entregable

Tres archivos editados:
- `deployment_decisions.yml`
- `operating_model.md`
- `release_checklist.md`

Archivo de apoyo para evaluación:
- `rubrica.md`

## Escenario base

Tomen las decisiones hechas en las sesiones 1 a 5 y consolídenlas en una primera versión lista para revisión de lanzamiento.

La solución debe:
- mantener coherencia entre producto, arquitectura, seguridad, observabilidad y UX
- hacer explícitos los tradeoffs
- dejar claro cómo se operará el agente
- definir un criterio mínimo para considerarlo listo

## Restricción

No deben construir nuevas piezas técnicas.
Solo deben cambiar:
- decisiones
- flags
- listas
- criterios de operación
- checklist de salida

## Preguntas guía

- ¿Qué se deja dentro y qué se deja fuera de la versión 1?
- ¿Qué tradeoff principal están aceptando?
- ¿Qué condición haría irresponsable lanzar todavía?
- ¿Quién revisa métricas, incidentes y ajustes?
- ¿Qué cambio requeriría aprobación explícita antes de desplegar?
- ¿Qué hace que esta primera versión sea operable y no solo demostrable?

## Criterios de evaluación

### Un buen resultado
- integra coherentemente las sesiones previas
- hace explícitos tradeoffs reales
- define un operating model básico
- establece un checklist de lanzamiento razonable
- mantiene una primera versión simple y gobernable

### Un mal resultado
- junta piezas sin coherencia
- no define ownership ni revisión
- no hace visibles los riesgos pendientes
- trata el lanzamiento como un paso técnico y no operativo
- sobrecarga la versión 1 con demasiada ambición

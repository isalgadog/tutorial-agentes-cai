# Challenge de la Sesión 4

## Diseñar monitoreo y observabilidad para un agente de IA de atención a clientes

## Objetivo del challenge

Definir una capa básica de observabilidad para operar el agente con más criterio.

La idea es decidir:
- qué eventos deben registrarse
- qué KPIs importan de verdad
- qué umbrales deben alertar
- qué señales requieren revisión manual
- cómo distinguir problemas de producto, riesgo y sistema

Todo esto editando archivos simples.

## Duración sugerida

15 a 25 minutos.

## Modalidad

- individual, o mejor
- en parejas o equipos de 3

## Entregable

Tres archivos editados:
- `observability.yaml`
- `dashboards.json`
- `eval_rubric.md`

Archivo de apoyo para evaluación:
- `rubrica.md`

## Escenario base

Tomen el agente definido en las sesiones anteriores y propongan un esquema mínimo de observabilidad para una primera versión operable.

La solución debe permitir:
- entender si el agente está ayudando
- detectar errores importantes
- observar señales de riesgo
- disparar revisiones razonables

## Restricción

No deben implementar dashboards reales ni pipelines de logging.
Solo deben cambiar:
- listas de eventos
- KPIs
- thresholds
- reglas de alerta
- criterios de evaluación

## Preguntas guía

- ¿Qué eventos vale la pena registrar desde el día 1?
- ¿Qué indicador puede verse bien pero esconder problemas?
- ¿Qué errores deben gatillar revisión rápida?
- ¿Qué parte del comportamiento del agente necesita revisión humana periódica?
- ¿Qué señales diferencian un problema técnico de uno de producto?
- ¿Qué sería suficiente observar al inicio sin caer en sobreinstrumentación?

## Criterios de evaluación

### Un buen resultado
- incluye métricas de producto, riesgo y sistema
- registra eventos útiles, no solo volumen
- define alertas razonables
- contempla revisión manual donde hace falta
- mantiene el esquema simple y operable

### Un mal resultado
- mide solo latencia o contención
- no incluye señales de riesgo
- no define umbrales accionables
- registra demasiado sin prioridad
- no conecta observabilidad con decisiones de operación

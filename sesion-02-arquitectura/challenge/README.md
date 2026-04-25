# Challenge de la Sesión 2

## Diseñar una arquitectura mínima viable para un agente de IA de atención a clientes

## Objetivo del challenge

Traducir decisiones de producto a una arquitectura simple, operable y de bajo costo.

La idea es definir:
- qué componentes necesita el sistema
- cómo fluye la información
- qué herramientas se habilitan
- qué tipo de memoria o persistencia se requiere
- qué decisiones ayudan a mantener bajo control la complejidad

Todo esto editando archivos simples.

## Duración sugerida

15 a 25 minutos.

## Modalidad

- individual, o mejor
- en parejas o equipos de 3

## Entregable

Tres archivos editados:
- `architecture.config.json`
- `tool_registry.json`
- `data_flow.md`

## Escenario base

Tomen el agente definido en la sesión 1 y propongan una arquitectura mínima viable para operarlo en un canal digital, con bajo costo y sin infraestructura pesada.

La solución debe ser:
- suficientemente útil para una primera versión
- suficientemente simple para mantenerse
- suficientemente clara para evolucionar más adelante

## Restricción

No deben programar nuevas funciones.
Solo deben cambiar:
- flags
- listas
- textos
- decisiones de activación o desactivación
- descripciones de flujo

## Preguntas guía

- ¿Qué componentes son realmente necesarios en la primera versión?
- ¿Qué cosas se pueden dejar fuera al inicio?
- ¿Dónde conviene persistir información y dónde no?
- ¿Qué herramientas necesita el agente y cuáles sería mejor no habilitar todavía?
- ¿Qué parte del sistema debe cargar la lógica principal?
- ¿Cómo mantener simple una arquitectura que luego pueda crecer?

## Criterios de evaluación

### Un buen resultado
- tiene componentes mínimos claros
- evita complejidad innecesaria
- distingue bien entre frontend, orquestación, modelo y datos
- define herramientas razonables
- muestra flujos de información comprensibles

### Un mal resultado
- introduce demasiadas piezas desde el inicio
- mezcla responsabilidades
- no distingue memoria de datos de negocio
- habilita herramientas sin criterio
- diseña una arquitectura difícil de operar para una primera versión

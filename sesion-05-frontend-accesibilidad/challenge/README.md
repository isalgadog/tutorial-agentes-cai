# Challenge de la Sesión 5

## Diseñar una experiencia frontend y accesible para un agente de IA de atención a clientes

## Objetivo del challenge

Traducir el comportamiento del agente a una interfaz más clara y usable.

La idea es definir:
- qué estados debe mostrar la interfaz
- cómo se comunican las acciones del agente
- qué confirmaciones necesita el usuario
- qué mensajes de error o handoff deben aparecer
- qué principios básicos de accesibilidad deben estar presentes

Todo esto editando archivos simples.

## Duración sugerida

15 a 25 minutos.

## Modalidad

- individual, o mejor
- en parejas o equipos de 3

## Entregable

Tres archivos editados:
- `ui_config.json`
- `conversation_states.yml`
- `accessibility_checklist.md`

Archivo de apoyo para evaluación:
- `rubrica.md`

## Escenario base

Tomen el agente definido en las sesiones anteriores y aterricen una experiencia de interfaz para una primera versión.

La solución debe:
- mostrar estados del sistema con claridad
- ayudar al usuario a entender qué está pasando
- reducir ambigüedad en acciones sensibles
- contemplar accesibilidad básica desde el inicio

## Restricción

No deben implementar una interfaz real.
Solo deben cambiar:
- flags
- textos
- estados
- listas de verificación
- reglas de confirmación

## Preguntas guía

- ¿Qué estados del agente necesita ver el usuario?
- ¿Qué acciones merecen confirmación explícita?
- ¿Qué mensaje ayuda cuando el agente escala a humano?
- ¿Qué parte de la experiencia puede ser confusa para alguien con baja familiaridad digital?
- ¿Qué haría inaccesible una interfaz aparentemente simple?
- ¿Qué mínimo viable de accesibilidad vale la pena exigir desde la versión 1?

## Criterios de evaluación

### Un buen resultado
- define estados claros del sistema
- comunica límites y siguientes pasos
- incluye confirmaciones razonables
- incorpora accesibilidad básica explícita
- mantiene consistencia con el producto y el riesgo del agente

### Un mal resultado
- deja estados ambiguos
- no explica handoffs o errores
- omite confirmaciones sensibles
- trata accesibilidad como detalle opcional
- prioriza apariencia sobre claridad de uso

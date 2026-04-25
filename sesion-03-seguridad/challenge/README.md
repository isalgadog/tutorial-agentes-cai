# Challenge de la Sesión 3

## Diseñar guardrails para un agente de IA de atención a clientes

## Objetivo del challenge

Traducir riesgos de seguridad y operación a políticas simples y claras.

La idea es definir:
- qué información debe protegerse
- qué acciones no puede ejecutar el agente
- cuándo debe escalar por riesgo
- qué herramientas requieren restricciones adicionales
- qué guardrails deben existir desde la primera versión

Todo esto editando archivos simples.

## Duración sugerida

15 a 25 minutos.

## Modalidad

- individual, o mejor
- en parejas o equipos de 3

## Entregable

Tres archivos editados:
- `guardrails.yml`
- `redaction_rules.json`
- `tool_permissions.yml`

Archivo de apoyo para evaluación:
- `rubrica.md`

## Escenario base

Tomen el agente y la arquitectura definidos en las sesiones anteriores y diseñen una capa inicial de seguridad y control.

La solución debe:
- proteger información sensible
- reducir exposición a acciones riesgosas
- limitar autonomía indebida
- escalar casos de alto riesgo

## Restricción

No deben programar controles técnicos nuevos.
Solo deben cambiar:
- reglas
- listas
- textos
- flags
- políticas de permiso y escalación

## Preguntas guía

- ¿Qué tipo de datos no debe repetir ni exponer el agente?
- ¿Qué acciones deben quedar prohibidas por defecto?
- ¿Qué herramientas podrían causar daño si se habilitan sin cuidado?
- ¿Qué temas ameritan revisión humana obligatoria?
- ¿Qué haría que un agente “útil” se vuelva inseguro?
- ¿Qué controles mínimos debe tener una primera versión?

## Criterios de evaluación

### Un buen resultado
- protege información sensible de forma explícita
- restringe acciones de alto riesgo
- define escalación por riesgo de manera razonable
- controla herramientas sensibles
- mantiene coherencia con el producto y la arquitectura

### Un mal resultado
- deja permisos demasiado amplios
- confía en que el agente “se portará bien”
- no protege datos sensibles
- no distingue entre lectura y escritura
- no define casos obligatorios de escalación

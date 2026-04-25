# Challenge de la Sesión 1

## Diseñar conceptualmente un agente de IA de atención a clientes

## Objetivo del challenge

Practicar decisiones de producto, no implementación compleja.

La idea es definir:
- qué hace el agente
- qué no hace
- cómo se comporta
- cómo se mide
- cuándo debe escalar

Todo esto editando archivos simples.

## Duración sugerida

15 a 25 minutos.

## Modalidad

- individual, o mejor
- en parejas o equipos de 3

## Entregable

Tres archivos editados:
- `agent_profile.yml`
- `success_metrics.json`
- `escalation_policy.yml`

Archivo de apoyo para evaluación:
- `rubrica.md`

## Escenario base

Una empresa quiere lanzar un agente de IA para atención a clientes en un canal digital.

El agente debe:
- resolver consultas frecuentes
- orientar al usuario en casos comunes
- servir como primera línea de atención

El agente no debe:
- tomar decisiones irreversibles
- resolver casos sensibles sin revisión
- actuar fuera de política

La meta es diseñar un agente útil pero prudente.

## Instrucciones para participantes

Editen los tres archivos base para definir un agente que tenga:

1. un propósito claro
2. alcance y no-alcance
3. una promesa de experiencia
4. métricas iniciales de éxito
5. una política razonable de escalación

## Restricción

No deben programar nuevas funciones.
Solo deben cambiar:
- variables
- listas
- textos
- thresholds
- reglas simples

## Preguntas guía

- ¿Qué consultas son suficientemente repetitivas y seguras para automatizar?
- ¿Qué consultas parecen simples, pero en realidad son riesgosas?
- ¿Qué promesa realista puede hacer el agente?
- ¿Qué error sería inaceptable?
- ¿Qué prefieren: escalar un poco antes o arriesgar una mala resolución?
- ¿Qué tendría que pasar para decir que este agente sí está ayudando?

## Criterios de evaluación

### Un buen resultado
- tiene alcance claro
- define no-alcance explícito
- no promete demasiado
- incluye métricas de riesgo
- tiene reglas de escalación razonables
- piensa en experiencia, no solo en automatización

### Un mal resultado
- quiere cubrir todo
- no distingue casos sensibles
- mide solo contención
- no define fallos graves
- hace promesas irreales
- trata la escalación como error absoluto

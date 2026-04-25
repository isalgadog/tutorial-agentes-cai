# Rúbrica de evaluación

## Challenge de la Sesión 3

Esta rúbrica sirve para evaluar si la propuesta de guardrails reduce riesgos importantes sin volver inútil al agente.

## Escala sugerida

- 1 = deficiente
- 2 = débil
- 3 = aceptable
- 4 = sólido
- 5 = excelente

---

## 1. Protección de información sensible

Se evalúa si el diseño identifica y protege datos que no deberían exponerse en respuestas o logs.

## 2. Restricción de acciones riesgosas

Se evalúa si el agente tiene límites claros para acciones irreversibles o de alto impacto.

## 3. Control de herramientas

Se evalúa si las herramientas habilitadas y bloqueadas reflejan criterio de riesgo y permisos mínimos.

## 4. Lógica de escalación por seguridad

Se evalúa si el diseño contempla casos donde la mejor decisión es escalar por riesgo, ambigüedad o política.

## 5. Coherencia con producto y arquitectura

Se evalúa si los guardrails tienen sentido para el tipo de agente y la arquitectura planteada en sesiones previas.

## 6. Balance entre utilidad y control

Se evalúa si los controles protegen sin dejar al agente incapaz de operar en casos comunes.

## Criterio de aprobación sugerido

El diseño está listo para pasar a la siguiente sesión si:
- protege datos sensibles clave
- bloquea o restringe acciones de alto riesgo
- define escalación razonable por seguridad
- aplica permisos mínimos a herramientas
- mantiene un balance aceptable entre utilidad y prudencia

# tutorial-agentes-cai

Tutorial práctico para diseñar agentes de IA de atención a clientes con una aproximación progresiva, conceptual y de bajo costo.

La propuesta del curso es que las personas participantes puedan explorar decisiones reales de producto, arquitectura, seguridad, observabilidad y experiencia sin depender de una infraestructura pesada. El enfoque está pensado para correr cómodamente con combinaciones como OpenClaw + Codex o OpenClaw + Gemini, usando retos guiados y archivos de configuración simples.

## Qué es este curso

Este repositorio reúne una serie de sesiones para aprender a diseñar un agente de IA de atención a clientes como un sistema operable, no solo como una demo conversacional.

A lo largo del curso se trabaja sobre cinco dimensiones principales:

1. producto y especificación
2. infraestructura y arquitectura
3. seguridad y guardrails
4. monitoreo y observabilidad
5. frontend y accesibilidad
6. integración, tradeoffs y operating model

## Enfoque del tutorial

Este tutorial está diseñado para:
- mantener baja la barrera de entrada
- evitar complejidad técnica innecesaria al inicio
- enseñar decisiones de diseño antes que implementación pesada
- usar retos prácticos donde la mayor parte del trabajo consiste en editar variables, listas, reglas y configuraciones

No busca que las personas construyan desde cero un sistema enterprise. Busca que entiendan cómo pensar, estructurar y operar un agente de IA de atención a clientes de forma razonable.

## Perfil sugerido de audiencia

Este material puede servir especialmente a:
- product owners y product managers
- technical product managers
- desarrolladores full stack
- tech leads
- arquitectos de solución
- especialistas en innovación
- personas de operaciones o experiencia digital

## Qué necesita una persona participante

Antes de arrancar, conviene revisar:
- [`PRERREQUISITOS.md`](./PRERREQUISITOS.md)

Ahí se documenta:
- qué tener instalado o conectado
- setup sugerido de OpenClaw
- herramientas recomendadas
- troubleshooting común

## Estructura del curso

### Sesión 1. Product thinking para un agente de IA de atención a clientes
- definición del problema y propósito del agente
- alcance y no-alcance
- promesa de experiencia
- métricas iniciales y lógica de escalación

### Sesión 2. Infraestructura y arquitectura para un agente de IA de atención a clientes
- componentes mínimos del sistema
- flujos de información
- herramientas, memoria y datos
- decisiones arquitectónicas de una primera versión

### Sesión 3. Seguridad y guardrails para un agente de IA de atención a clientes
- riesgos principales
- acciones restringidas
- redacción de información sensible
- permisos y escalación por seguridad

### Sesión 4. Monitoreo y observabilidad para un agente de IA de atención a clientes
- métricas de producto, riesgo y sistema
- eventos clave
- dashboards mínimos
- criterios de revisión manual

### Sesión 5. Frontend y accesibilidad para un agente de IA de atención a clientes
- estados del sistema
- mensajes y confirmaciones
- handoff y errores
- principios básicos de accesibilidad

### Sesión 6. Integración, tradeoffs y operating model para un agente de IA de atención a clientes
- integración de todas las decisiones anteriores
- tradeoffs de la versión 1
- modelo inicial de operación
- checklist de salida y lanzamiento

## Cómo está organizado el repositorio

Cada sesión incluye normalmente:
- un `README.md` corto de contexto
- un `explicacion.md` con el resumen conceptual
- una carpeta `challenge/` con archivos editables
- una `rubrica.md` para evaluación

## Estructura del repositorio

```text
PRERREQUISITOS.md
sesion-01-product-thinking/
  README.md
  explicacion.md
  challenge/
    README.md
    agent_profile.yml
    success_metrics.json
    escalation_policy.yml
    rubrica.md

sesion-02-arquitectura/
  README.md
  explicacion.md
  challenge/
    README.md
    architecture.config.json
    tool_registry.json
    data_flow.md
    rubrica.md

sesion-03-seguridad/
  README.md
  explicacion.md
  challenge/
    README.md
    guardrails.yml
    redaction_rules.json
    tool_permissions.yml
    rubrica.md

sesion-04-observabilidad/
  README.md
  explicacion.md
  challenge/
    README.md
    observability.yaml
    dashboards.json
    eval_rubric.md
    rubrica.md

sesion-05-frontend-accesibilidad/
  README.md
  explicacion.md
  challenge/
    README.md
    ui_config.json
    conversation_states.yml
    accessibility_checklist.md
    rubrica.md

sesion-06-integracion/
  README.md
  explicacion.md
  challenge/
    README.md
    deployment_decisions.yml
    operating_model.md
    release_checklist.md
    rubrica.md
```

## Resultado esperado del curso

Al terminar el recorrido, una persona debería poder:
- definir un agente de atención como producto
- proponer una arquitectura mínima viable
- establecer controles y guardrails básicos
- identificar qué observar en operación
- aterrizar principios de UX y accesibilidad
- integrar todo en una primera versión operable

## Estado

Este repositorio seguirá evolucionando con mejoras editoriales, ejemplos de solución y materiales complementarios.

# Sesión 3. Seguridad y guardrails para un agente de IA de atención a clientes

## Objetivo

Que la audiencia entienda cómo traducir riesgos de atención y uso de IA a guardrails simples y operables, antes de entrar a controles técnicos avanzados.

## Agenda sugerida, 90 min

### 1. Apertura, 10 min
Idea clave: un agente útil pero sin límites puede convertirse en un riesgo operativo.

### 2. Riesgos principales en agentes de atención, 20 min
Revisar riesgos como:
- prompt injection
- fuga de información
- uso indebido de herramientas
- exceso de autonomía
- respuestas fuera de política
- manejo incorrecto de datos sensibles

### 3. Qué debe controlar el producto, 20 min
Trabajar controles sobre:
- temas sensibles
- acciones restringidas
- información que nunca debe exponerse
- casos que requieren revisión humana
- límites del agente frente a incertidumbre

### 4. Guardrails simples y políticas, 15 min
Traducir controles a artefactos como:
- políticas de uso de herramientas
- reglas de redacción
- listas de acciones prohibidas
- condiciones de escalación

### 5. Errores de diseño frecuentes, 10 min
Revisar errores como:
- confiar demasiado en el prompt
- no separar lectura de escritura
- dejar permisos muy amplios
- no distinguir riesgo de negocio y riesgo técnico

### 6. Challenge práctico, 15 min
Editar archivos simples de seguridad:
- `guardrails.yml`
- `redaction_rules.json`
- `tool_permissions.yml`

## Aprendizajes esperados

Al final, la persona debe poder:
- identificar riesgos principales de un agente de atención
- traducir esos riesgos a políticas simples
- definir acciones restringidas
- proponer reglas básicas de redacción y escalación
- entender que la seguridad también es diseño de producto

## Mensaje final

Los guardrails no son un accesorio del agente. Son parte de lo que hace que pueda operar de forma confiable.

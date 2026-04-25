# Sesión 4. Monitoreo y observabilidad para un agente de IA de atención a clientes

## Objetivo

Que la audiencia entienda cómo observar el desempeño de un agente en operación, combinando métricas de producto, señales de riesgo y datos técnicos básicos.

## Agenda sugerida, 90 min

### 1. Apertura, 10 min
Idea clave: un agente no se termina cuando se despliega, empieza una etapa de operación y aprendizaje.

### 2. Qué conviene observar, 20 min
Distinguir entre:
- métricas de producto
- métricas de experiencia
- métricas de riesgo
- métricas técnicas

### 3. Eventos y señales útiles, 20 min
Trabajar eventos como:
- handoff
- uso de herramientas
- errores
- latencia
- respuestas fuera de alcance
- repeticiones del usuario

### 4. Dashboards y alertas mínimas, 15 min
Discutir qué vale la pena ver en una primera versión:
- KPIs principales
- umbrales de alerta
- señales que ameritan revisión manual

### 5. Errores frecuentes de observabilidad, 10 min
Revisar errores como:
- medir solo latencia o solo contención
- loggear demasiado sin criterio
- no distinguir incidente técnico de problema de producto
- no instrumentar handoffs o fallos de seguridad

### 6. Challenge práctico, 15 min
Editar archivos simples:
- `observability.yaml`
- `dashboards.json`
- `eval_rubric.md`

## Aprendizajes esperados

Al final, la persona debe poder:
- distinguir métricas de producto, riesgo y sistema
- proponer eventos clave para observar al agente
- definir dashboards mínimos útiles
- establecer umbrales básicos de alerta
- entender que la observabilidad es parte de operar el producto

## Mensaje final

Lo que no se observa bien en un agente se corrige tarde o se interpreta mal. Operar bien exige mirar más que volumen y latencia.

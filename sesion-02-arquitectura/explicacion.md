# Sesión 2. Infraestructura y arquitectura para un agente de IA de atención a clientes

## Objetivo

Que la audiencia entienda cómo traducir la definición de producto a una arquitectura mínima viable y operable, sin caer todavía en complejidad innecesaria.

## Agenda sugerida, 90 min

### 1. Apertura, 10 min
Idea clave: la arquitectura debe servir al producto definido, no al revés.

### 2. Componentes principales del sistema, 20 min
Identificar piezas mínimas:
- frontend o canal
- backend u orquestador
- modelo
- herramientas
- memoria
- capa de datos

Idea clave: no toda arquitectura necesita todos los componentes desde el día 1.

### 3. Flujos de información, 20 min
Trabajar cómo circula la información entre:
- usuario
- interfaz
- orquestador
- modelo
- herramientas
- persistencia

Idea clave: una buena arquitectura hace explícitas las fronteras y responsabilidades.

### 4. Decisiones de diseño mínimas, 15 min
Discutir tradeoffs como:
- stateless vs stateful
- memoria local vs externa
- knowledge base local vs remota
- una sola capa de servicio vs varias capas
- simplicidad vs extensibilidad

### 5. Riesgos arquitectónicos tempranos, 10 min
Revisar riesgos comunes:
- acoplamiento excesivo
- demasiadas piezas desde el inicio
- confusión entre memoria, contexto y datos de negocio
- mezclar lógica de producto con detalles de proveedor

### 6. Challenge práctico, 15 min
Editar archivos simples de arquitectura:
- `architecture.config.json`
- `tool_registry.json`
- `data_flow.md`

## Aprendizajes esperados

Al final, la persona debe poder:
- identificar los componentes mínimos de un agente
- justificar una arquitectura simple
- explicar flujos de información básicos
- distinguir entre memoria, herramientas y datos
- elegir decisiones razonables para una primera versión

## Mensaje final

Una buena arquitectura para un agente no es la más sofisticada. Es la que sirve al producto con la menor complejidad necesaria.

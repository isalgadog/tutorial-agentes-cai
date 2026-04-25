# Flujo de datos base

1. El usuario envía una consulta desde el frontend.
2. El frontend entrega la solicitud al orquestador.
3. El orquestador prepara contexto de sesión y decide si consulta herramientas.
4. El modelo genera una respuesta o propone un handoff.
5. Si aplica, el orquestador consulta una herramienta permitida.
6. El resultado vuelve al modelo o al orquestador para construir la respuesta final.
7. La respuesta se entrega al frontend.
8. Se registra información básica de operación y trazabilidad.

## Preguntas para ajustar

- ¿Qué pasos deben persistir datos?
- ¿Qué parte del flujo necesita memoria de sesión?
- ¿Cuándo conviene usar herramienta y cuándo solo responder con contexto?
- ¿Qué acciones nunca deberían formar parte del flujo automático?

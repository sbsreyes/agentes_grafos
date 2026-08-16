# agentes_grafos

Este repositorio describe, de forma sencilla, un flujo de agentes por grafos usando LangChain:

1. **Entrada del usuario**: se recibe la solicitud o problema.
2. **Nodo planificador**: un agente analiza la intención y decide qué pasos seguir.
3. **Nodos especializados**: cada agente resuelve una tarea concreta (búsqueda, análisis o generación).
4. **Ruteo por grafo**: según el resultado de cada nodo, el flujo avanza al siguiente nodo adecuado.
5. **Nodo de síntesis**: se combinan los resultados y se genera una respuesta final clara.

La idea central es representar el proceso como un grafo, donde cada nodo es una capacidad del sistema y cada arista define cómo continúa la ejecución.
# Agents-GenAI

A diferencia de los sistemas de LLMs tradicionales, que solo generan respuestas basadas en su entrenamiento y son más reactivos, o inclusive que pueden llegar a generar respuestas más genéricas, los Agentes son sistemas más autónomos que pueden:

* Razonar y tomar decisiones propias
* Ejecutar acciones concretas - utilizando diferentes herramientas (APIs, búsquedas, cálculos, conexión con otros sistemas)
* Mantener memoria y contexto de interacciones previas

Mientras un LLM tradicional solo te diría qué hacer, un Agente puede entender, planificar y ejecutar acciones por sí mismo para resolver tareas.
Podrá razonar qué herramientas son apropiadas a usar.
La diferencia está en la capacidad de acción, no solo en el conocimiento.

A las acciones de Razonar y Actuar de los agentes les denominaremos "ReAct"

En este reopositorio se hará uso de un agente encargado de definir si es bueno invertir o no en una empresa, a través del uso de Gemini (LLM) y Google Finance (nuestro tool) para determinar esta decisión.

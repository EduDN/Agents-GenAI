# Agents-GenAI with LangChain

A diferencia de los sistemas de LLMs tradicionales, que solo generan respuestas basadas en su entrenamiento y son más reactivos, o inclusive que pueden llegar a generar respuestas más genéricas, los Agentes son sistemas más autónomos que pueden:

* Razonar y tomar decisiones propias
* Ejecutar acciones concretas - utilizando diferentes herramientas (APIs, búsquedas, cálculos, conexión con otros sistemas)
* Mantener memoria y contexto de interacciones previas

Mientras un LLM tradicional solo te diría qué hacer, un Agente puede entender, planificar y ejecutar acciones por sí mismo para resolver tareas.
Podrá razonar qué herramientas son apropiadas a usar.
La diferencia está en la capacidad de acción, no solo en el conocimiento.

A las acciones de Razonar y Actuar de los agentes les denominaremos "ReAct"

En este reopositorio se hará uso de un agente encargado de definir si es bueno invertir o no en una empresa, a través del uso de Gemini (LLM) y Google Finance (nuestro tool) para determinar esta decisión.

Tener en cuenta que dentro del uso de los agentes podremos tener acceso a diversas tools, a continuación comparto la lista de herramientas disponibles en LangChain: https://python.langchain.com/v0.1/docs/integrations/tools/

![image](https://github.com/user-attachments/assets/8793a944-8a51-43f7-b59b-efff158d3589)



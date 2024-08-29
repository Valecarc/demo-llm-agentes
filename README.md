# Demo-llm-agentes / prompt-engineering

1. Crea tu propia API key en la página de Groq [aquí](https://console.groq.com/login).
2. Reemplaza tu key en la sección donde se define el modelo:

```python
# Definir el modelo LLM:
llm_llama = ChatGroq(
    temperature=0,
    model_name="llama-3.1-70b-versatile", # Puedes cambiar el nombre del modelo por cualquiera de los que ofrece Groq
    api_key="tu_api_key"
)
```

3. Para mayor facilidad, puedes ejecutar estos Jupyter Notebooks en Google Colab. Solo debes ir ejecutando celda por celda para replicar los resultados.

4. Puedes modificar los diferentes prompts en cada uno de los ejemplos para obtener distintos resultados, o puedes utilizar el template base para crear un grupo de agentes para tu propia solución.

Espero que estos pequeños ejemplos les hayan abierto los ojos a las posibilidades que el "prompt engineering", los "llm" y la IA en general tienen para ofrecer. Los animo 

¡Ahora los invito a explorar este fascinante mundo! a investigar más sobre este tema, a seguir aprendiendo y a considerar cómo pueden aplicarlo en sus carreras y en su vida cotidiana.
El conocimiento es una herramienta poderosa, la Inteligencia Artificial y el prompt engineering pueden ser grandes aliados para impulsar su crecimiento profesional.

¡Happy coding!

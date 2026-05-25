# AgenteIA
Vamos a crear un agente de IA en WhatsApp para una peluqueria como proyecto final de la asignatura de digitalización.

1. Arquitectura y Base de Datos (DevOps)
Su función: Crear la estructura inicial del repositorio vacío, configurar el entorno virtual o contenedores (Docker) para que todos trabajéis igual, y diseñar la base de datos (PostgreSQL/Supabase).

Misión crítica: Definir los modelos de datos (Tablas de Clientes, Citas, Servicios, Horarios).

2. Integración de WhatsApp (Comunicaciones)
Su función: Conectar el servidor con la pasarela de WhatsApp (usando librerías como Baileys o APIs externas).

Misión crítica: Conseguir que el sistema reciba el mensaje del cliente, extraiga el número de teléfono, el texto, y se lo pase al Backend; luego, recibir la respuesta del Backend y enviársela al cliente.

3. El "Cerebro" de la IA (Ingeniería de Prompts y Agentes)
Su función: Configurar la conexión con OpenAI (u otro proveedor), diseñar el System Prompt (la personalidad y reglas de la peluquería) y estructurar las herramientas (Function Calling / Agentes) que usará la IA.

Misión crítica: Hacer que la IA sea capaz de decidir con precisión: "El cliente quiere una cita, voy a ejecutar la función del sistema para buscar huecos disponibles".

4. Lógica de Negocio y API (Backend Core)
Su función: Desarrollar las funciones lógicas internas del sistema y los endpoints intermedios.

Misión crítica: Crear la lógica que valida si una cita es posible, calcula la duración del servicio seleccionado y conecta las peticiones de la IA con la base de datos.

5. Base de Conocimiento y RAG (Recuperación de Información)
Su función: Implementar un sistema RAG (Retrieval-Augmented Generation) para que la IA responda preguntas frecuentes con precisión basándose en documentos de la peluquería (tarifas complejas, políticas de cancelación, tratamientos específicos).

Misión crítica: Crear la base de datos vectorial (o sistema de búsqueda de texto) para que la IA no invente información sobre los servicios del local.

6. Panel de Control del Peluquero (Frontend)
Su función: Desarrollar una interfaz web sencilla (puede ser con React, Vue o incluso plantillas de servidor) para que el dueño de la peluquería gestione el negocio de forma visual.

Misión crítica: Crear una pantalla donde el peluquero pueda ver el calendario de citas que la IA va agendando automáticamente y un listado de clientes.

# TaipyBot

# Chatbot con Taipy, LangChain y LLM basado en RAG

Este proyecto tiene como objetivo construir un chatbot inteligente utilizando las tecnologías **Taipy**, **LangChain** y **Modelos de Lenguaje de Última Generación (LLM)**, basado en el enfoque **RAG (Retrieval-Augmented Generation)**. El chatbot será capaz de responder de manera precisa y eficiente a las preguntas de los usuarios.

---

## Tecnologías Utilizadas

### 1. **Taipy**
- Framework para construir aplicaciones de datos interactivas y personalizadas.
- Proporciona una interfaz de usuario poderosa y herramientas de gestión de flujo de datos.

### 2. **LangChain**
- Framework para la construcción de aplicaciones impulsadas por modelos de lenguaje.
- Facilita la integración de múltiples modelos y el encadenamiento de tareas complejas.

### 3. **Modelos de Lenguaje de Última Generación (LLM)**
- Implementación de modelos de lenguaje avanzados para generación y comprensión de texto.
- Compatible con GPT y otros modelos de alto rendimiento.

### 4. **RAG (Retrieval-Augmented Generation)**
- Enfoque que combina recuperación de información relevante y generación de respuestas.
- Permite al chatbot buscar información en bases de datos o documentos para proporcionar respuestas fundamentadas.

---

## Funcionalidades

1. **Procesamiento de Preguntas:**
   - Responde preguntas abiertas y específicas de los usuarios.
   - Capaz de manejar preguntas complejas con múltiples dependencias.

2. **Recuperación de Información:**
   - Busca en fuentes de datos relevantes para obtener información precisa.
   - Integra la recuperación con la generación para respuestas fundamentadas.

3. **Interfaz de Usuario Personalizada:**
   - Diseñada utilizando Taipy para una experiencia intuitiva.
   - Interfaz interactiva que mejora la experiencia del usuario.

4. **Modularidad:**
   - Estructura del código modular para facilitar la personalización y escalabilidad.

---

## Instalación

1. **Clonar el Repositorio**
```bash
git clone https://github.com/usuario/chatbot-taipy-langchain.git
cd chatbot-taipy-langchain
```

2. **Configurar un Entorno Virtual**
```bash
python3 -m venv .venv
source .venv/bin/activate  # En Windows: .venv\Scripts\activate
```

3. **Instalar Dependencias**
```bash
pip install -r requirements.txt
```
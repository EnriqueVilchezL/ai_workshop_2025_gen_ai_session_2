# ai_workshop_2025_gen_ai_session_2

# Taller: Construyendo una App con Gen AI (LLMs locales)  

Este taller tiene como objetivo enseñar cómo utilizar modelos de lenguaje de gran tamaño (LLMs) de manera local utilizando [Ollama](https://ollama.com/), e integrarlos con herramientas como [Langchain](https://www.langchain.com/) y [Gradio](https://www.gradio.app/) para construir una aplicación conversacional funcional.

---

## 🔧 ¿Qué se hace en este taller?

1. **Instalación de dependencias**  
   Se instala y configura **Ollama** para correr modelos localmente en la máquina de Colab. También se instalan bibliotecas clave como `langchain`, `gradio`, `ollama` y `pypdf`.

2. **Uso de LLMs locales con Ollama**  
   Se configura un servidor local usando `ollama serve`, se descarga un modelo (por ejemplo, `llama3.1:8b`) y se prueba la generación de texto.

3. **Interacción avanzada con Langchain**  
   Se introduce cómo Langchain ayuda a estructurar mensajes con plantillas y a mantener el historial de conversaciones (memoria conversacional). También se trabaja con generación dinámica de texto token a token.

4. **Creación de una aplicación con Gradio**  
   Se implementa una interfaz web para conversar con el modelo desde el navegador.

5. **Análisis de archivos**  
   Se extiende la funcionalidad para permitir cargar archivos PDF o TXT, analizarlos y obtener respuestas del modelo sobre su contenido.

---

## 📚 Bibliotecas utilizadas

- [`ollama`](https://pypi.org/project/ollama/): Ejecutar y gestionar LLMs de forma local.
- [`langchain`](https://www.langchain.com/): Orquestar interacciones con modelos de lenguaje.
- [`gradio`](https://www.gradio.app/): Crear interfaces web para modelos de ML.
- `langchain_community`: Complementos para proveedores no incluidos en el paquete base.
- `pypdf`: Lectura de archivos PDF en Python.

---

## 🚀 Cómo ejecutarlo

Este proyecto está pensado para correr directamente en **Google Colab**. Para comenzar:

1. Abre el notebook en Colab desde este enlace:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/EnriqueVilchezL/ai_workshop_2025_gen_ai_session_2/blob/main/incomplete.ipynb)

2. Asegúrate de seleccionar un entorno con GPU (`Runtime > Change runtime type > GPU`).

3. Ejecuta cada celda paso a paso siguiendo las instrucciones del notebook.

---

## 🛠 Requisitos

- Cuenta de Google para usar Colab.
- Acceso a Internet para descargar modelos y bibliotecas.
- Familiaridad básica con Python (recomendado).

---

## 💡 Notas

- Ollama no está diseñado para funcionar en entornos en la nube como Colab de forma nativa, pero este taller muestra cómo emular su ejecución.
- El modelo descargado puede tardar un poco según su tamaño.
- Gradio puede no funcionar con su interfaz visual completa dentro de Colab; se recomienda probar localmente para una experiencia más fluida.

---

## 📬 Contacto

Para dudas o comentarios, contactar a [@EnriqueVilchezL](https://github.com/EnriqueVilchezL)
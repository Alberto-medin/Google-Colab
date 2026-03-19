# Google-Colab
2.3 Practica 12-13 de Marzo, sistemas RAG (Retrieval-Augmented Generation) utilizando Python en Google Colab
# Laboratorio: Sistema RAG (Retrieval-Augmented Generation)

## Descripción

Este repositorio contiene un laboratorio introductorio sobre **sistemas RAG (Retrieval-Augmented Generation)** desarrollado en **Python utilizando Google Colab**.  

El propósito de esta práctica es comprender cómo los sistemas modernos de inteligencia artificial combinan **búsqueda de información y modelos de lenguaje** para generar respuestas más precisas basadas en documentos previamente almacenados.

El sistema desarrollado permite consultar una base de documentos y obtener respuestas generadas por un modelo de IA utilizando recuperación semántica.

---

# Objetivo

Comprender de forma práctica el funcionamiento de un sistema **RAG**, el cual combina:

- Búsqueda semántica
- Embeddings
- Bases de datos vectoriales
- Modelos de lenguaje

Esto permite generar respuestas basadas en información recuperada desde una base de conocimiento.

---

# Tecnologías Utilizadas

- **Python**
- **Google Colab**
- **Embeddings**
- **Bases de datos vectoriales**
- **Modelos de lenguaje (LLM)**

---

# ¿Qué es un sistema RAG?

RAG significa **Retrieval-Augmented Generation** (Generación Aumentada por Recuperación).

Este enfoque mejora la generación de texto de los modelos de lenguaje al **buscar información relevante antes de generar la respuesta**.

El proceso generalmente sigue estos pasos:

1. Se recibe una pregunta del usuario.
2. La pregunta se convierte en un **embedding** (vector numérico).
3. Se busca en una **base de datos vectorial** los documentos más similares.
4. Los documentos encontrados se envían junto con la pregunta al **modelo de lenguaje**.
5. El modelo genera una respuesta basada en esa información.

De esta manera, el sistema puede responder utilizando información específica almacenada previamente.

---

# Funcionamiento del Laboratorio

El laboratorio desarrollado en Google Colab sigue el siguiente flujo:

1. **Carga de documentos**  
   Se cargan textos que formarán la base de conocimiento.

2. **Creación de embeddings**  
   Los documentos se transforman en representaciones vectoriales que permiten medir similitud semántica.

3. **Almacenamiento en base de datos vectorial**  
   Los embeddings se guardan para poder realizar búsquedas rápidas.

4. **Consulta del usuario**  
   El usuario realiza una pregunta al sistema.

5. **Búsqueda semántica**  
   El sistema encuentra los documentos más relacionados con la consulta.

6. **Generación de respuesta**  
   El modelo de lenguaje utiliza esos documentos para generar una respuesta informativa.

---


- **RAG_Laboratorio.ipynb**: Notebook de Google Colab con el laboratorio ejecutado.
- **README.md**: Explicación del proyecto.
- **documentos/**: Archivos utilizados como base de conocimiento.

---

# Cómo Ejecutar el Proyecto

1. Abrir el archivo **RAG_Laboratorio.ipynb** en Google Colab.
2. Ejecutar las celdas en orden.
3. Cargar los documentos de ejemplo.
4. Realizar consultas al sistema.
5. Observar cómo el modelo genera respuestas utilizando la información recuperada.

---

# Resultados Observados

Durante las pruebas realizadas en el laboratorio se pudo observar que el sistema es capaz de:

- Encontrar documentos relacionados con la consulta del usuario.
- Generar respuestas basadas en el contenido de esos documentos.
- Mejorar la precisión de las respuestas al utilizar información recuperada.

Esto demuestra cómo los sistemas RAG permiten que los modelos de lenguaje trabajen con **bases de conocimiento externas**.

---

# Conclusión

Los sistemas RAG representan una de las arquitecturas más importantes en aplicaciones actuales de inteligencia artificial.  

Al combinar **búsqueda de información y generación de lenguaje natural**, permiten construir sistemas más confiables, actualizables y útiles para resolver consultas basadas en conocimiento específico.

---

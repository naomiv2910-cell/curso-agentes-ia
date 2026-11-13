# Hugging Face Agents Course — Ciencia de Datos

**Estudiante:** Naomi Valentina Mosquera Perea  
**Universidad:** Universidad Externado de Colombia  
**Programa:** Ciencia de Datos  
**Usuario Hugging Face:** `naovl`

## 1. Descripción del proyecto

Este repositorio reúne las actividades y notebooks desarrollados durante el curso **Hugging Face Agents Course**, cuyo propósito fue comprender el funcionamiento de los agentes de inteligencia artificial, sus componentes y las herramientas que les permiten interactuar con información externa para resolver tareas.

A lo largo del curso trabajé con Google Colab, Python y diferentes herramientas para experimentar con modelos de lenguaje y comprender cómo pueden integrarse en sistemas capaces de realizar tareas de manera semiautónoma.

## 2. Actividades desarrolladas

### Unidad 1. Fundamentos de agentes

Durante esta unidad exploré los conceptos principales relacionados con los agentes de inteligencia artificial, incluyendo el uso de modelos de lenguaje, instrucciones, herramientas y ciclos de razonamiento y ejecución.

También realicé ejercicios prácticos para comprender cómo se estructura un agente y cómo puede utilizar herramientas externas.

Los notebooks correspondientes se encuentran en la carpeta `unidad-01`.

### Proyecto final. Agente para resolver GAIA

Como aplicación de los conocimientos adquiridos, desarrollé un agente en Python utilizando **Gemini** como modelo de lenguaje y herramientas de búsqueda web para investigar y responder preguntas del benchmark GAIA.

El desarrollo incluyó la consulta de preguntas mediante una API, la búsqueda de información relevante, la generación de respuestas y su posterior envío al evaluador oficial.

El agente fue ejecutado en Google Colab y su código también se publicó en Hugging Face.

**Resultado final: 35 % de precisión (7 respuestas correctas de 20).**

Este resultado permitió superar el umbral mínimo del 30 % establecido para la evaluación GAIA.

## 3. Tecnologías utilizadas

- Python y Google Colab.
- Google Gemini API.
- Hugging Face.
- Herramientas de búsqueda web mediante DDGS.
- API de evaluación GAIA.
- Git y GitHub.

## 4. Estructura del repositorio

```text
unidad-01/
├── dummy_agent_library_gemini.ipynb
├── primer_agente_smolagents_gemini.ipynb
├── gaia_final_agent_gemini.ipynb
└── GAIA_Agente_Gemini_Entrega_Limpia.ipynb

README.md
```

El notebook `GAIA_Agente_Gemini_Entrega_Limpia.ipynb` presenta una versión organizada del trabajo final, con explicaciones del procedimiento, desarrollo del agente y resultados obtenidos.

## 5. Resultados y aprendizajes

El principal aprendizaje fue comprender que desarrollar un agente de inteligencia artificial implica mucho más que enviar preguntas a un modelo de lenguaje. También requiere seleccionar herramientas, recuperar información, controlar errores y evaluar la calidad de las respuestas.

Durante el desarrollo se presentaron dificultades relacionadas con los límites de uso de las API, la disponibilidad de archivos y las restricciones para desplegar el agente en Hugging Face. Para continuar el trabajo utilicé Google Colab como entorno de ejecución y un Static Space para publicar el código.

La primera evaluación obtuvo un 25 % de precisión. Después de revisar y corregir dos respuestas, la puntuación aumentó al 35 %, resultado que quedó registrado en el evaluador oficial.

Esta experiencia también permitió identificar limitaciones importantes de los agentes basados en modelos de lenguaje, especialmente cuando no disponen de fuentes suficientes para verificar sus respuestas.

## 6. Enlaces y evidencias

**Código del agente en Hugging Face:**  
https://huggingface.co/spaces/naovl/gaia-gemini-agent/tree/main

**Perfil de Hugging Face:**  
https://huggingface.co/naovl

**Evaluación GAIA:**  
35 % — 7/20 respuestas correctas.

**Certificación:**  
Hugging Face Agents Course — Certificate of Excellence.  
Fecha de expedición: 13 de noviembre de 2026.

## 7. Observaciones finales

El curso me permitió llevar a la práctica conceptos de inteligencia artificial generativa y agentes, integrando herramientas que complementan los conocimientos adquiridos durante mi formación en Ciencia de Datos.

Aunque el agente logró superar el porcentaje mínimo requerido, los resultados evidenciaron oportunidades de mejora en la búsqueda de información, la validación de respuestas y el procesamiento de archivos externos.

El proyecto constituye una primera aproximación práctica al desarrollo y evaluación de agentes de inteligencia artificial.

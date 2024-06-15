# CHATGPT

Este repositorio contiene el código para un proyecto basado en ChatGPT, el modelo de IA que se utiliza es Llama-3-8B-Instruct-q4f32_1-MLC-1k de Meta.
Este modelo se ejecuta en el navegador utilizando webGPU.

## Descripción

El proyecto incluye una interfaz web sencilla y un script de web workers en JavaScript. Está diseñado para demostrar la funcionalidad básica de un chatbot.

Los web workers son una característica de JavaScript que permite ejecutar scripts en segundo plano, separados del hilo principal de ejecución de la página web. Esto es particularmente útil en proyectos que requieren la realización de tareas intensivas en computación o que necesitan ejecutar procesos largos sin bloquear la interfaz de usuario.

## Archivos

- `index.html`: Contiene la estructura HTML de la página web.
- `worker.js`: Contiene el script de web workers en JavaScript.

## Repositorios Utilizados

Este proyecto se basó en el siguiente repositorio:
- [web-llm](https://github.com/mlc-ai/web-llm/tree/main) de mlc-ai.

WebLLM es un motor de inferencia LLM en el navegador de alto rendimiento que lleva la inferencia de modelos de lenguaje directamente a los navegadores web con aceleración de hardware. Todo se ejecuta dentro del navegador sin soporte de servidor y se acelera con WebGPU.

WebLLM es totalmente compatible con la API OpenAI . Es decir, puede usar la misma API OpenAI en cualquier modelo de código abierto localmente, con funcionalidades que incluyen transmisión, modo JSON, llamada de funciones (WIP), etc.


## Uso

1. Clona el repositorio.
2. Abre `index.html` en tu navegador para interactuar con el chatbot.

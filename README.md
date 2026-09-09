# deck-base

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/narratech/deck-base/blob/main/deck-base.ipynb)

Este repositorio contiene el punto de partida para la práctica [Análisis de Mazos de Magic](https://narratech.com/es/aprendizaje-automatico-y-mineria-de-datos/introduccion/analisis-de-mazos-de-magic/) de la asignatura Aprendizaje Automático y Minería de Datos. 

## Objetivo de la práctica
El objetivo de la práctica es realizar un análisis estadístico introductorio sobre un supuesto conjunto de datos con telemetría del juego *Magic: The Gathering Arena* utilizando únicamente Python (con sus estructuras de datos, bucles, condicionales y bibliotecas estándar).

El equipo de diseño del juego necesita verificar dos quejas recurrentes en la comunidad:
1. **Dominio de Mono-Red Aggro:** Se sospecha que este mazo tiene una tasa de victorias (*Winrate*) desproporcionada.
2. **Ventaja del primer jugador (*On the Play*):** Se sospecha que empezar jugando influye demasiado en el resultado final de la partida.

Tu trabajo como analista es procesar el archivo `match_logs.json` y responder a estas preguntas con datos.

## Estructura del repositorio

* **`match_logs.json`**: Fichero de datos, similar al que se podría descargar de *17Lands*, con la telemetría de 150 partidas.
* **`deck-base.ipynb`**: Plantilla del cuaderno interactivo a completar por el alumno. Contiene la descripción de las características y las celdas donde se deberá escribir el código.

## Restricciones Técnicas

* **Prohibido el uso de bibliotecas de terceros:** No se permite importar `numpy`, `pandas`, `scipy`, `matplotlib` ni bibliotecas similares.
* **Bibliotecas permitidas:** Solo las bibliotecas estándar de Python (módulos como `json`, `math`, etc.).

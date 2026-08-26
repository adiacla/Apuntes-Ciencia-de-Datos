#  Guía de Estudio: Modelos Secuenciales en TensorFlow y Keras

¡Bienvenido a este repositorio! Este material ha sido diseñado como una **guía interactiva de estudio práctico y teórico**[cite: 9]. Aquí aprenderás los fundamentos esenciales sobre la construcción, entrenamiento e inspección de redes neuronales utilizando **TensorFlow** y **Keras**[cite: 9].

>  **IMPORTANTE:** Los conceptos, estructuras de código y ejercicios explicados en este cuaderno forman parte de los **temas evaluados en el próximo quiz**[cite: 9]. Utiliza este repositorio como tu material principal de repaso.

---

##  ¿Qué vas a aprender?

**1. Fundamentos Teóricos de Keras**
* **Construcción de Arquitecturas:** Aprenderás las 3 formas estándar de definir modelos en Keras (lista en `Sequential`, método incremental `.add()`, y la **API Funcional**)[cite: 9].
* **Entorno de Trabajo:** Inspección del sistema (Python `3.12.12`), verificación de librerías y comprobación de soporte para GPU mediante `!nvidia-smi`[cite: 9].

**2. Práctica Aplicada (Paso a Paso)**
* **Regresión Lineal Simple:** Definición y entrenamiento de un perceptrón (una sola neurona)[cite: 9].
* **Ejercicio Celsius a Fahrenheit:** Implementación de un modelo que aprende de forma autónoma la conversión matemática $Fahrenheit = (Celsius \times 1.8) + 32$[cite: 9].
* **Estructura de Datos:** Creación de tensores/arreglos NumPy, preparación de características/etiquetas y separación de datos de entrenamiento (80%) y validación (20%)[cite: 9].

---

##  Puntos Clave para el Examen

Asegúrate de dominar los siguientes elementos presentes en el código:

* **Comparativa de APIs:** Identificar sintácticamente `model_a`, `model_b` y `model_c`[cite: 9].
* **Flujo de Entrenamiento:** Uso correcto de los métodos `.compile()`, `.fit()` y evaluación de métricas[cite: 9].
* **Dimensiones de Entrada:** Manejo de la forma de los datos (`input_shape`) tanto para problemas sintéticos multivariables `(1000, 20)` como unidimensionales `(12,)`[cite: 9].

---

##  ¿Qué encontrarás en el repositorio?

Al abrir el cuaderno de Jupyter (`.ipynb`), serás guiado a través de **17 celdas interactivas** organizadas lógicamente[cite: 9]:

* **Celdas 1 - 3:** Verificación y preparación del entorno de ejecución[cite: 9].
* **Celdas 4 - 8 (Teoría):** Definición comparativa de modelos secuenciales y funcionales con datos sintéticos (1,000 muestras)[cite: 9].
* **Celdas 9 - 17 (Práctica):** Ejercicio guiado de conversión de temperatura con 12 muestras de datos realistas, compilación, ajuste de hiperparámetros e inspección de resultados[cite: 9].

---

##  Requisitos Rápidos

Para ejecutar y experimentar con el código localmente con VsC o en Google Colab:
* **Python 3.12+**[cite: 9]
* Librerías: `tensorflow`, `numpy`, `matplotlib`

¡Abre el cuaderno, ejecuta las celdas en orden, analiza cada sección y prepárate para el quiz!

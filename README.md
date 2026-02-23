# Redes Neuronales desde Cero

Este repositorio documenta mi proceso de aprendizaje en **Deep Learning**, donde he implementado diversas arquitecturas únicamente con **NumPy**, sin utilizar frameworks como PyTorch o TensorFlow. El objetivo ha sido entender la matemática real detrás de cada algoritmo.

El proyecto está estructurado siguiendo todos los pasos fundamentales para comprender el funcionamiento interno de las redes neuronales, desde la unidad más simple hasta modelos de lenguaje complejos. Además, la arquitectura y el diseño de estas redes están **inspirados en PyTorch**, utilizando una lógica de capas, estados y flujos de datos que facilita la transición a frameworks profesionales.

---

## Implementaciones Realizadas

### 1. Fundamentos
* Desde la neurona más básica ($y = x \cdot w$).
* Desarrollo de redes multicapa con **retropropagación (Backpropagation)**.
* Implementación de funciones de activación y optimizadores manuales.



### 2. NLP y Semántica
* Procesamiento de lenguaje natural mediante la creación de **Word Embeddings**.
* Análisis del espacio vectorial y cálculo de similitud entre palabras.
* Uso de matrices de pesos para representar conceptos semánticos.

### 3. Redes Recurrentes (RNN)
* Implementación de una red de memoria para procesar secuencias de texto.
* Uso de **Backpropagation Through Time (BPTT)** para aprender dependencias temporales.
* Manejo de estados ocultos para arrastrar contexto a través de la secuencia.



### 4. Razonamiento Lógico
* Entrenamiento de modelos sobre el **dataset bAbI** (Facebook Research).
* Resolución de tareas de respuesta a preguntas (**QA**) mediante la acumulación y decodificación de estados ocultos.
* Implementación de funciones **Softmax** para la predicción de vocabulario.

---

## 🛠️ Tecnologías utilizadas
* **Python 3.x**
* **NumPy** (Álgebra lineal y manipulación de matrices)
* **Datasets:** bAbI, IMDB y otros ejemplos sintéticos.

---

*Inspirado en la filosofía de "entender construyendo" para dominar las bases del aprendizaje profundo.*

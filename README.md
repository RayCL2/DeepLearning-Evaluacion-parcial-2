# DeepLearning-Evaluacion-parcial-2
Repositorio correspondiente a la evaluacion parcial 2 de deeplearning de duocuc
Autores: Basthian Bascuñan - Gibran Beiza

# EP2 – Técnicas de Regularización en Redes Neuronales MLP

## Descripción del Proyecto

Este proyecto corresponde a la **Evaluación Parcial N°2 de Deep Learning**, cuyo objetivo es implementar distintas técnicas de **regularización** sobre un modelo **MLP (Multilayer Perceptron)** previamente desarrollado en la EP1.

El propósito principal fue reducir el problema de **overfitting** identificado en la evaluación anterior y mejorar la capacidad de generalización del modelo sobre datos no vistos.

Las técnicas implementadas fueron:

- **L2 Regularization**
- **Dropout**
- **Batch Normalization**
- **Early Stopping**

El dataset utilizado corresponde a **IMDB Movie Reviews**, orientado a clasificación binaria de sentimientos (**positivo / negativo**).

---

## Requisitos

Para ejecutar el proyecto se requiere:

### Librerías Python

```python
tensorflow
keras
numpy
pandas
matplotlib
scikit-learn
```

### Entorno recomendado

Se recomienda utilizar:

**Google Colab**

o bien

**Python 3.10+ con Jupyter Notebook**

---

## Instrucciones de Ejecución

### Paso 1: Abrir el notebook

Abrir el archivo `.ipynb` correspondiente a la EP2 en **Google Colab**.

---

### Paso 2: Ejecutar librerías

Ejecutar la primera celda del notebook para importar las librerías necesarias.

---

### Paso 3: Cargar el dataset

Ejecutar las celdas correspondientes a:

- Carga del dataset IMDB
- Tokenización del texto
- Padding de secuencias
- División de datos de entrenamiento y prueba

---

### Paso 4: Ejecutar el modelo baseline

Ejecutar el modelo **MLP baseline** de la EP1 para obtener las métricas de referencia y detectar el problema de overfitting.

---

### Paso 5: Ejecutar técnicas de regularización

Ejecutar secuencialmente las siguientes secciones del notebook:

1. **L2 Regularization**
2. **Dropout**
3. **Batch Normalization**
4. **Early Stopping**

Cada técnica incluye:

- entrenamiento del modelo
- métricas de evaluación
- gráficos comparativos
- análisis de resultados

---

### Paso 6: Comparación final

Ejecutar la sección final del notebook para generar:

- tabla comparativa de métricas
- gráficos de comparación
- conclusiones finales

---

## Resultados Esperados

Se espera observar una reducción del problema de **overfitting** respecto al baseline de la EP1.

La técnica con mejor desempeño fue:

**L2 Regularization (`lambda = 0.001`)**

presentando mejoras en:

- Accuracy
- Recall
- F1-score

respecto al modelo baseline.

---

## Autor

**Basthian Luis Bascuñan Santander** 
**Gibran Beiza**
Asignatura: **Deep Learning**

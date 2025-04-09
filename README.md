# Técnicas de Inteligencia Artificial – Tarea 3

## Objetivo

El objetivo de esta tarea es implementar una red neuronal (NN) capaz de clasificar tres clases de objetos (personas) usando un conjunto de datos compuesto por imágenes. Esta tarea se basa en la tarea #2 y utiliza el mismo conjunto de datos, el cual incluye imágenes de Bruce, Neil y Pam.

📌 El informe debe tener un máximo de 10 páginas, incluyendo imágenes.  
❌ **No** incluyas código en el reporte principal; todo el código debe entregarse como un archivo Colab (`.ipynb`).

---

## Tarea 1: Crear el conjunto de datos

- Toma imágenes de los miembros del equipo (mínimo 10 por persona).
- Mantén una resolución baja (256 × 256 px), formato `.jpeg`.
- Aumenta el conjunto de datos:
  - Reflejar (flip), rotar y redimensionar imágenes.
  - Añadir ruido a parte del conjunto.
  - Duplica el tamaño del conjunto original como mínimo.
- Crea `data loaders` de 15 imágenes tanto para entrenamiento como para prueba.

### 📌 Discute el conjunto de datos
Incluye observaciones sobre variedad, balance entre clases, calidad, y los efectos de la aumentación.

---

## Tarea 2: Crear una red neuronal ancha (Wide NN)

- Crea una red neuronal de **una sola capa**, pero con **muchas neuronas** (función de activación: **ReLU**).
- Implementa el ciclo de **forward** y de **entrenamiento**.
- Determina el número "óptimo" de neuronas:
  - Compara métricas como **precisión**, **pérdida**, tiempo de entrenamiento y tamaño de pesos para distintas configuraciones.

### 📌 Discute y justifica tu elección final

---

## Tarea 3: Crear una red neuronal profunda (Deep NN)

- Crea una red neuronal **profunda** con **M capas**, cada una con **N = 50 neuronas**.
- Usa función de activación **ReLU**.
- Implementa los ciclos de **forward** y **entrenamiento**.
- Determina el número "óptimo" de capas:
  - Compara precisión, pérdida y rendimiento para distintas profundidades.

### 📌 Discute y justifica tu elección final

---

## Tarea 4: Crear una CNN

- Diseña una **Red Neuronal Convolucional** (CNN) con al menos:
  - Una **capa convolucional**
  - Una **capa de pooling**
  - Una **capa completamente conectada** con \( N = 50 \) neuronas
- Usa función de activación **ReLU**.
- Ajusta hiperparámetros:
  - Tamaño de kernel, número de canales, padding, stride, etc.
- Compara el rendimiento para diferentes configuraciones.

### 📌 Discute y justifica tu elección final

---

## Tarea 5: Conclusiones

- Discute los resultados generales y **presenta evidencia suficiente** para tus elecciones.
- Recomendaciones para esta sección:
  - Analiza los pasos de entrenamiento y prueba.
  - ¿Cuál fue mejor en tu caso: red ancha, profunda o CNN?
  - Comenta sobre el tiempo de entrenamiento, complejidad y precisión final.

---

## 📎 Entregables

- 📄 Informe (PDF o documento) **máx. 10 páginas**, sin código.
- 📁 Notebook Colab (`.ipynb`) con todo el código y visualizaciones.

---

## 👥 Autores

- Diana Marcela Bello López – dbellol@unal.edu.co / dbellol 
- Cristian Tovar – correo / cstovar  
- Curso: Técnicas de Inteligencia Artificial  
- Universidad Nacional de Colombia  
- 2025-1 / 2025

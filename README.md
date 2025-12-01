# 🛒 Proyecto: Análisis de Datos de Instacart

## 📘 Introducción
Este proyecto utiliza un subconjunto modificado del dataset de Instacart, una plataforma de entrega de comestibles.  
El objetivo principal es realizar un proceso completo de análisis de datos que incluye carga, limpieza, validación, transformación y análisis exploratorio (EDA).  
El dataset contiene valores faltantes, duplicados e inconsistencias creadas a propósito para simular un entorno real de trabajo.

---

## ✨ Funcionalidades

### 🔍 1. Descripción de los datos
- Exploración general del dataset.
- Revisión de estructura y tipos de datos.
- Uso de métodos como `info()`, `head()` y `shape()`.

### 🧹 2. Limpieza y preprocesamiento
- Corrección de tipos de datos.
- Eliminación de duplicados.
- Identificación y tratamiento de valores ausentes.
- Normalización de columnas en:
  - `orders`
  - `products`
  - `aisles`
  - `departments`
  - `order_products`
- Creación de funciones para validar columnas y su compatibilidad con conversiones de tipo.

### 📊 3. Análisis exploratorio (EDA)
- Revisión de rangos de columnas como:
  - `order_hour_of_day`
  - `order_dow`
- Visualizaciones:
  - Clientes por hora del día.
  - Actividad por día de la semana.
  - Distribución de días entre pedidos.
- Identificación de patrones de comportamiento del usuario.

### 📚 4. Diccionario de datos
- Descripción de cada tabla y columna del dataset para facilitar su interpretación.

### 📝 5. Revisión y retroalimentación
- Se incluyen comentarios del revisor y las respuestas correspondientes siguiendo la dinámica del proyecto.

---

## 🛠️ Herramientas utilizadas
- 🐍 **Python 3**
- 📓 **Jupyter Notebook**
- 📦 Librerías:
  - **pandas** — manipulación de datos
  - **numpy** — cálculos numéricos
  - **matplotlib** — visualización gráfica

---

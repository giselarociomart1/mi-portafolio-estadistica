# Desafío – Regresión Lineal 📈🐟

## Descripción del proyecto

Este trabajo corresponde a un desafío de **Regresión Lineal**, cuyo objetivo es construir modelos predictivos para estimar el **peso de peces** a partir de sus **dimensiones físicas**.

El análisis se realiza sobre un conjunto de datos que registra ventas en el mercado de **7 especies comunes de peces**, incluyendo variables como longitudes, altura y ancho. A partir de estas características se exploran relaciones estadísticas y se desarrollan modelos de regresión.

---

## Dataset

Cada fila del dataset representa un pez individual e incluye las siguientes variables:

* **Species**: Especie del pez.
* **Weight**: Peso del pez (variable objetivo).
* **Length1, Length2, Length3**: Diferentes medidas de longitud.
* **Height**: Altura del pez.
* **Width**: Ancho del pez.

Además, se crea una **nueva variable derivada**:

* **Volume**: Volumen del pez, asumiéndolo como un cilindro.

---

## Objetivos del desafío

1. Crear una nueva columna que represente el **volumen del pez**, asumiendo forma cilíndrica.
2. Analizar la **correlación** entre las variables, tanto de forma numérica como gráfica.
3. Evaluar si la inclusión del volumen mejora la correlación con el peso.
4. Construir un **modelo de regresión lineal simple** entre volumen y peso, evaluarlo y graficarlo.
5. Analizar el comportamiento del modelo al aplicarlo **por separado a cada especie**.
6. Construir un **modelo de regresión múltiple** utilizando dos o más variables predictoras.

---

## Metodología

* Limpieza y exploración inicial de los datos.
* Creación de la variable **volumen** utilizando la fórmula del cilindro: [ V = \pi r^2 h ]
* Análisis de correlaciones mediante matrices y gráficos.
* Entrenamiento de modelos de **regresión lineal simple y múltiple**.
* Evaluación de los modelos utilizando métricas de desempeño.
* Visualización de resultados para facilitar la interpretación.

---

## Herramientas utilizadas

* **Python**
* **Pandas** y **NumPy** para manipulación de datos.
* **Matplotlib / Seaborn** para visualización.
* **Scikit-learn** para modelado y evaluación.
* **Jupyter Notebook** como entorno de desarrollo.

---

## Resultados esperados

* Comprender la relación entre las dimensiones físicas de los peces y su peso.
* Evaluar el impacto del volumen como variable explicativa.
* Comparar modelos generales vs. modelos segmentados por especie.
* Identificar qué variables aportan mayor capacidad predictiva.

---

## Conclusión

Este trabajo permite aplicar conceptos clave de **regresión lineal**, análisis exploratorio de datos y evaluación de modelos, combinando fundamentos estadísticos con un enfoque práctico orientado al análisis de datos reales.

---

## Autor

**Gisela Martínez**

📚 Técnico Superior en Análisis de Sistemas
📊 Formación en Análisis de Datos y Ciencia de Datos

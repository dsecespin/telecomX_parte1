---

# 📊 Telecom X - Análisis de Evasión de Clientes

## 📌 Descripción del Proyecto

Este proyecto forma parte del desafío **Telecom X**, cuyo objetivo es analizar la **evasión de clientes (Churn)** en la empresa. La compañía enfrenta una **alta tasa de cancelación de servicios**, lo que afecta la retención y el crecimiento. A través de un **análisis exploratorio de datos (EDA)** y la creación de métricas clave, se busca **identificar patrones y factores que influyen en la pérdida de clientes**, aportando información estratégica para la toma de decisiones.

---

## 🎯 Objetivos del Análisis

* Comprender los factores que impulsan la evasión de clientes.
* Identificar patrones y tendencias relacionadas con la cancelación.
* Proporcionar insights que sirvan como base para modelos predictivos y estrategias de retención.

---

## ✅ Habilidades y Conceptos Practicados

* **Extracción de Datos desde API (JSON)**
* **ETL (Extracción, Transformación y Carga)**
* **Limpieza y Preparación de Datos**
* **Análisis Exploratorio de Datos (EDA)**
* **Visualización de Datos con Python**
* **Generación de Insights Estratégicos**

---

## 🔗 Fuente de Datos

Los datos provienen de la API de Telecom X en formato **JSON**:

* [📂 Archivo JSON](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json)
* [📂 Repositorio Original](https://github.com/ingridcristh/challenge2-data-science-LATAM)

---

## 🛠 Tecnologías Utilizadas

* **Python 3.x**
* **Pandas** → Manipulación y análisis de datos.
* **NumPy** → Cálculos y métricas estadísticas.
* **Matplotlib / Seaborn** → Visualización de datos.
* **Requests** → Extracción de datos desde API.
* **Jupyter Notebook** → Desarrollo y presentación del análisis.

---

## 🔍 Flujo del Análisis

1. **Extracción de Datos**

   * Importación del dataset desde la API.
   * Conversión a DataFrame para facilitar la manipulación.

2. **Conocimiento del Dataset**

   * Exploración inicial de columnas y tipos de datos.
   * Consulta del diccionario de datos.

3. **Limpieza y Preparación de Datos**

   * Detección y manejo de valores ausentes, duplicados e inconsistencias.
   * Corrección de errores de formato y categorías.
   * Creación de columna **`Cuentas_Diarias`** (facturación diaria).

4. **Análisis Descriptivo**

   * Cálculo de estadísticas descriptivas (media, mediana, desviación estándar).
   * Distribución de variables categóricas y numéricas.

5. **Análisis de Evasión (Churn)**

   * Visualización de la proporción de clientes que cancelaron.
   * Análisis de churn por variables categóricas (género, tipo de contrato, método de pago).
   * Análisis de churn por variables numéricas (tiempo de contrato, gasto total).

6. **Informe Final**

   * Introducción al problema.
   * Descripción de limpieza y tratamiento.
   * Resultados del EDA y visualizaciones.
   * **Insights clave** para la toma de decisiones.
   * **Recomendaciones estratégicas**.

---

## 📈 Ejemplo de Visualizaciones

* Distribución del churn (clientes activos vs cancelados).
* Heatmap de correlaciones.
* Análisis de churn por tipo de contrato y método de pago.
* Distribución del gasto total vs churn.

---

## 📜 Conclusiones e Insights

Al finalizar el análisis, se espera obtener:

* Variables más relevantes asociadas al churn.
* Perfiles de clientes con mayor riesgo de cancelación.
* Estrategias sugeridas para **reducir la evasión**.

---

## ✅ Próximos Pasos

* Implementar **modelos predictivos** para estimar churn.
* Desarrollar un dashboard interactivo para monitoreo.
* Evaluar impacto de las recomendaciones en métricas de retención.

---

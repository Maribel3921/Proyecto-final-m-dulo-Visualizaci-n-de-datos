# Proyecto-final-m-dulo-Visualizaci-n-de-datos
Analisís estadístico de parámetros de operación en columna de destilación
# Proyecto: Análisis de Parámetros de Operación en Columna de Destilación con R

---

## 🚀 Visión General del Proyecto

Este proyecto fue realizado como parte del Módulo Visualización y análisis de datos. Se enfoca en el análisis estadístico y la visualización de los parámetros de operación clave en una **columna de destilación industrial**. Utilizando datos simulados que replican condiciones reales, el objetivo es comprender el comportamiento dinámico del proceso, identificar tendencias, detectar anomalías.

---

## 🎯 Objetivos del Análisis

* **Identificar Tendencias y Variabilidad:** Explorar el comportamiento estadístico de variables como temperaturas de platos, presión y caudales a lo largo de un periodo de operación.
* **Detección de Anomalías:** Reconocer valores atípicos o fluctuaciones inusuales que puedan indicar problemas operativos.
* **Visualización de Datos:** Crear representaciones gráficas claras e informativas que faciliten la interpretación de los patrones de comportamiento del sistema.

---

## 📊 Metodología y Datos

Los datos utilizados para este proyecto provienen de un dataset simulado que describe el comportamiento de una columna de destilación a lo largo de **450 horas**, con mediciones capturadas cada **0.1 horas**. El análisis se realizó en **R Markdown**, siguiendo una metodología que incluyó:

1.  **Carga e Inspección Inicial de Datos:** Verificación de la estructura, dimensiones y nombres de las columnas.
2.  **Limpieza y Transformación de Datos:**
    * Eliminación de filas completamente vacías.
    * Manejo de valores `NA` (reemplazo por la media en columnas numéricas).
    * Creación de la variable **Tiempo (h)**.
    * Cálculo de la **Relación de Reflujo (L/D)**, un parámetro crucial para la eficiencia y el costo operativo de la columna.
3.  **Análisis Estadístico Descriptivo:** Resumen de las principales estadísticas de las variables.
4.  **Visualización de Datos:** Generación de gráficos (ej., perfiles de temperatura) para entender las dinámicas del proceso.

---


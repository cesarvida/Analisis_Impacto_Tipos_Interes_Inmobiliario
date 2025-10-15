# Analisis_Impacto_Tipos_Interes_Inmobiliario
Este proyecto de ciencia de datos analizó el impacto de la política monetaria (Tasa Hipotecaria a 30 años) y la Inflación (IPC) sobre el Índice de Precios de la Vivienda (CSUSHPINSA) de EE. UU. entre 2015 y 2025, utilizando Python (Pandas, Seaborn) y statsmodels.
# 📈 Análisis del Impacto de la Política Monetaria en el Mercado Inmobiliario de EE. UU. (2015-2025)

## 📌 Resumen Ejecutivo

Este proyecto de Ciencia de Datos explora la relación entre las decisiones de la Reserva Federal (Tasa Hipotecaria a 30 años) y la Inflación (IPC) con el Índice de Precios de la Vivienda (CSUSHPINSA) en el mercado estadounidense. A través de un análisis de series temporales y Modelos de Regresión, se contrasta la correlación a largo plazo con la causalidad económica real.

**Conclusión Clave:** La Regresión Lineal Múltiple ($\text{R-squared} = 0.986$) demostró que, al aislar la inflación, un aumento de un punto porcentual en la Tasa Hipotecaria se asocia con una **disminución de 6.58 unidades** en el índice de precios, confirmando que la política monetaria ha sido un freno efectivo para el crecimiento desbocado del precio de la vivienda.

---

## 🛠️ Tecnologías y Metodología

| Componente | Herramientas Clave |
| :--- | :--- |
| **Lenguaje** | Python (Entorno Virtual) |
| **Librerías** | Pandas, NumPy, Matplotlib, Seaborn, **statsmodels** |
| **Metodología** | Análisis de Series Temporales, EDA, Regresión Lineal Múltiple (OLS) |

## 📊 Visualización Clave del EDA

El siguiente gráfico ilustra la fuerte correlación visual entre el estímulo monetario (bajas tasas pre-2022) y el crecimiento acelerado de los precios, seguido por la estabilización a partir de la subida de tasas en 2022-2023.



*Nota: La correlación positiva a largo plazo entre tasas y precios se debe a la tendencia alcista compartida por la economía.*

---

## 📂 Estructura del Repositorio

| Archivo | Descripción |
| :--- | :--- |
| **`1.0_Ingesta_y_Revision_Inicial.ipynb`** | Ingesta de datos de FRED y revisión de la frecuencia mixta inicial. |
| **`2.0_Preprocesamiento_y_EDA_Inicial.ipynb`** | Limpieza, estandarización de frecuencia mensual y generación de gráficos de series temporales. |
| **`3.0_Analisis_Regresion_y_Modelado.ipynb`** | Implementación del modelo OLS, análisis de coeficientes, P-values y discusión de la multicolinealidad. |
| **`datos_analisis_mensual.csv`** | Conjunto de datos limpio y listo para el análisis (mensual). |
| **`requirements.txt`** | Lista de librerías para la reproducibilidad del entorno. |

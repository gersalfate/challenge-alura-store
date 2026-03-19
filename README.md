# 📊 Challenge: Business Intelligence - Alura Store Latam

![Status](https://img.shields.io/badge/STATUS-FINALIZADO-green)
![Python](https://img.shields.io/badge/Python-3.12-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20datos-orange)

## 📌 Descripción del proyecto

Este proyecto desarrolla un análisis de **Business Intelligence (BI)** para la cadena "Alura Store Latam", realizado como parte del programa **Oracle Next Education (ONE)** de **Oracle + Alura Latam**. El objetivo estratégico es resolver un problema de optimización de activos: identificar, mediante evidencia cuantitativa, cuál de las 4 tiendas de la cadena presenta el desempeño más crítico para recomendar su venta estratégica al propietario (Sr. Juan).

## 🚀 Metodología y lógica de ingeniería

El análisis se estructuró en cuatro fases técnicas para garantizar la integridad de las conclusiones:

1.  **ETL y normalización:** Consolidación de 4 fuentes de datos (datasets en formato CSV) y estandarización de tipos de datos, incluyendo la conversión de series temporales para análisis cronológico.
2.  **Análisis de tendencias:** Implementación de medias móviles (rolling mean de 6 meses) para suavizar la volatilidad estacional y visualizar la tendencia real de ingresos a largo plazo.
3.  **Evaluación de KPIs críticos:**
    * **Facturación total:** Agregación de ingresos totales por sucursal.
    * **Mix de productos:** Análisis de volumen de ventas por categoría (Muebles, Electrónicos, etc.).
    * **Voz del cliente:** Procesamiento de calificaciones promedio para medir la salud del servicio y lealtad de marca.
4.  **Análisis geográfico:** Visualización de la dispersión de ventas mediante coordenadas (latitud/longitud) y mapas de calor por precio para identificar clústeres de desempeño.

## 🛠️ Stack tecnológico

* **Lenguaje:** Python 3.12
* **Librerías core:**
    * `pandas`: Limpieza, agregación de datos y manipulación de DataFrames.
    * `matplotlib` & `seaborn`: Generación de visualizaciones ejecutivas (barras, líneas de tendencia, diagramas de torta y scatter plots geográficos).
* **Entorno:** Google Colab.

## 📈 Conclusiones estratégicas (Resumen ejecutivo)

Tras el análisis multidimensional de las 4 sucursales, se determinó que la **Tienda 4** es la candidata óptima para la desinversión debido a los siguientes hallazgos:

* **Deficiencia en facturación:** Es la sucursal con los menores ingresos totales de toda la cadena.
* **Tendencia crítica:** Presenta la caída más pronunciada en su media móvil de ventas hacia el final del periodo de estudio.
* **Baja satisfacción:** Registra una de las calificaciones promedio más bajas, lo que indica un riesgo operativo y de retención de clientes.

## 👤 Autor

* **Gerardo Salfate** ([LinkedIn](https://www.linkedin.com/in/gerardo-salfate/) | [GitHub](https://github.com/gersalfate))

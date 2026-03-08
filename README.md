# 📊 Análisis de Evasión de Clientes (Churn) - Telecom X

![Data Science](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-green.svg)

## 🎯 Objetivo del Proyecto
Este proyecto busca identificar los factores clave que influyen en la deserción de clientes de la empresa **Telecom X**. A través de un análisis de datos profundo (EDA) y cálculos de correlación, se identificaron patrones de comportamiento y se generaron recomendaciones estratégicas para reducir la tasa de abandono actual.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn.
* **Herramientas:** Google Colab, GitHub, JSON API.

## 📋 Proceso de Trabajo
1. **Extracción y Carga (ETL):** Obtención de datos desde una API JSON y normalización de estructuras.
2. **Limpieza de Datos:** Gestión de inconsistencias (eliminación de 224 registros con valores vacíos) y conversión de tipos de datos.
3. **Feature Engineering:** Creación de la métrica `Cargo_Diario` y `Conteo_Servicios` para medir el ecosistema del cliente.
4. **Estandarización:** Traducción de variables al español y binarización de categorías (`Yes/No` a `1/0`).
5. **Análisis Estadístico:** Cálculo de **Correlación de Pearson** para cuantificar la relación entre variables numéricas y la evasión.

## 🔍 Hallazgos Clave (Basados en Datos)
* **Relación Inversa Crítica:** La antigüedad tiene una correlación negativa de **-0.35** con el abandono; a mayor permanencia, menor riesgo de fuga.
* **Efecto de Anclaje:** Los clientes con más servicios adicionales (Seguridad, Backup, Soporte) presentan tasas de evasión significativamente menores.
* **Factor Precio:** Los cargos mensuales/diarios tienen una correlación positiva (**+0.19**), confirmando que el costo es un detonante directo del Churn.
* **Perfil de Riesgo:** El **26.5%** de la cartera está en fuga, concentrándose principalmente en el segmento de adultos mayores y contratos mensuales.



## 🚀 Recomendaciones Estratégicas
* **Fidelización Temprana:** Implementar programas de retención intensivos durante los primeros **18 meses** (periodo de mayor riesgo).
* **Estrategia de Bundling:** Incentivar la contratación de servicios adicionales para aumentar la barrera de salida del cliente.
* **Optimización de Pagos:** Promover el cambio de métodos manuales (cheque electrónico) a automáticos para reducir la fricción financiera.

---
**Desarrollado por:** [Hanni Javiera](https://github.com/HanniJaviera)

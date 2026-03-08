# 📊 Análisis de Evasión de Clientes (Churn) - Telecom X

![Data Science](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-green.svg)

## 🎯 Objetivo del Proyecto
Este proyecto busca identificar los factores clave que influyen en la deserción de clientes de la empresa **Telecom X**. A través de un análisis de datos profundo (EDA), se identificaron patrones de comportamiento y se generaron recomendaciones estratégicas para reducir la tasa de abandono actual.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn.
* **Herramientas:** Google Colab, GitHub.

## 📋 Proceso de Trabajo
1. **Extracción y Carga (ETL):** Obtención de datos desde una API JSON y normalización de estructuras.
2. **Limpieza de Datos:** - Gestión de inconsistencias (eliminación de 224 registros con valores vacíos ocultos).
   - Conversión de tipos de datos (`Total_Charges` de texto a numérico).
3. **Feature Engineering:** Creación de la métrica `Cargo_Diario` para analizar el micro-gasto del usuario.
4. **Estandarización:** Traducción de variables al español y binarización de categorías (`Yes/No` a `1/0`) para análisis matemático.
5. **Análisis Exploratorio (EDA):** Identificación de tendencias mediante visualizaciones estadísticas.

## 🔍 Hallazgos Clave
* **Tasa de Evasión:** El **26.5%** de los clientes abandonan el servicio.
* **Factor Precio:** Los clientes que se van pagan un **21% más** diariamente en comparación con los clientes leales.
* **Periodo Crítico:** El mayor riesgo de fuga ocurre en los primeros **18 meses** de antigüedad.
* **Contratos:** Los contratos "Mes a Mes" representan el mayor volumen de deserción.

## 🚀 Recomendaciones Estratégicas
* **Fidelización:** Implementar planes de lealtad para clientes nuevos durante su primer año.
* **Migración de Contratos:** Ofrecer descuentos a usuarios de planes mensuales para que migren a contratos anuales.
* **Métodos de Pago:** Incentivar el uso de débito automático para reducir la fricción en el pago manual.

---
**Desarrollado por:** [Hanni Javiera](https://github.com/HanniJaviera)

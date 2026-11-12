# 📚 Análisis de Datos Masivos, Machine Learning y Storytelling: Caso 1 - Deserción Escolar en Bolivia (EH2025)
Repositorio oficial para el desarrollo del caso de estudio de maestría enfocado en la resolución de un problema social crítico mediante el uso de microdatos de la **Encuesta de Hogares 2025 (EH2025)** del Instituto Nacional de Estadística (INE) de Bolivia.
---
## 🎯 Pregunta de Investigación
> **¿Cuáles son los factores sociodemográficos, económicos y geográficos que más influyen en la deserción escolar en Bolivia?**
---
## 🗂️ Estructura del Repositorio
El proyecto se encuentra organizado bajo una estructura modular orientada a la reproducibilidad científica:
- 📁 `data/`: Microdatos crudos (.sav) de la EH2025
- 📁 `notebooks/`: Jupyter Notebooks limpios y ejecutables (`DesercionEscolarBolivia.ipynb`)
- 📁 `src/`: Scripts de Python modulares
- 📁 `outputs/`: Reportes EDA en HTML (Sweetviz) y datasets procesados
- 📁 `docs/`: Informe final de Storytelling y recursos visuales
---
## 🛠️ Stack Tecnológico
- **Ingesta y Consultas:** DuckDB
- **Manipulación:** Pandas, NumPy, Pyreadstat
- **EDA Automatizado:** Sweetviz
- **Visualización:** Plotly
- **Machine Learning & XAI:** Scikit-Learn (K-Means), XGBoost y Random Forest
---
## 📊 Principales Hallazgos y Métricas
- **Rendimiento Predictivo:** Los modelos supervisados alcanzaron un AUC-ROC de ~0.8788 (XGBoost) bajo validación cruzada estratificada.
- **Factores Críticos:** La edad del estudiante y el perfil socioeconómico del hogar (Clúster) son los predictores determinantes de la deserción escolar.
---
## 📌 Citación Obligatoria
> Instituto Nacional de Estadística (INE), *Encuesta de Hogares 2025 (EH2025)*. Disponible en: http://anda.ine.gob.bo/index.php/catalog/256.

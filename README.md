# Análisis Exploratorio de Datos y Business Intelligence: EcoEnergy Solutions

Este proyecto realiza una auditoría completa, análisis exploratorio de datos (EDA) y una solución de Business Intelligence para optimizar el consumo energético y el control de costes de la compañía **EcoEnergy Solutions**.

##  Acceso a los Recursos
* **Cuaderno de Análisis (Google Colab):** (https://colab.research.google.com/drive/1n1IzK7N99OErBqs9PuRQI-Fp91gTfXzP?usp=sharing)
* **Panel Interactivo (Google Looker Studio):** (https://datastudio.google.com/reporting/ced29444-093a-4faa-add2-66a67444046d)
* **Informe Ejecutivo:** El informe resumido de hallazgos se encuentra en formato PDF en la carpeta de informes.

##  Resumen de Hallazgos Clave
* **Principal Driver:** Se determinó una correlación del **0.89** entre el consumo en kWh y el coste total de las facturas.
* **Segmentación:** Los contratos de tipo **Comercial** dominan la demanda en todas las regiones, siendo las zonas **Centro** y **Norte** las de mayor impacto.
* **Auditoría de Datos:** Se detectó e informó una anomalía en las variables de CO₂ y energía renovable, las cuales operan de forma aleatoria (sintética) en el origen de datos actual, permitiendo prever correcciones en el sistema de ingeniería de la empresa.

##  Tecnologías Utilizadas
* **Python 3** (Pandas, NumPy)
* **Seaborn & Matplotlib** (Visualización estadística)
* **Google Looker Studio** (Dashboarding e interactividad)
* **Google Drive API / Gspread** (Análisis y automatización del flujo de datos)

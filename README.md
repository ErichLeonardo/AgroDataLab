# AgroDataLab

AgroDataLab es una aplicación web desarrollada con Django para el análisis de datos agrícolas procedentes de sensores EnviroPro.

El sistema permite importar archivos CSV, visualizar datos ambientales mediante gráficas, detectar anomalías energéticas y aplicar modelos de Machine Learning para predecir situaciones de riesgo relacionadas con la humedad del suelo.

## Funcionalidades

- Importación de datos EnviroPro mediante CSV.
- Visualización de humedad, temperatura, batería y panel solar.
- Gráficas temporales por registros, meses y años.
- Predicción de humedad baja mediante modelos de Machine Learning.
- Detección automática de alertas energéticas.
- Generación automática de recomendaciones.
- Gestión de alertas y recomendaciones mediante CRUD.

## Tecnologías utilizadas

- Python
- Django
- Pandas
- Scikit-Learn
- Joblib
- SQLite
- Bootstrap 5
- Chart.js

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/ErichLeonardo/AgroDataLab.git

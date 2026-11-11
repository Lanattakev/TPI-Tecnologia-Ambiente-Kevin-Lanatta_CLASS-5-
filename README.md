# TPI - Tecnología y Ambiente

**Alumno:** Kevin Lanatta  
**Profesor:** Daniel Petruccelli  
**Institución:** ISFT N.º 199  

## Objetivo
Analizar y predecir el consumo eléctrico de un edificio de oficinas mediante Machine Learning y proponer medidas de eficiencia energética.

## Datos utilizados
- Fuente: Building Data Genome 2.
- Edificio: Panther_office_Karla.
- Período analizado: junio de 2016 a diciembre de 2017.
- Registros horarios utilizados: 13.896.
- Fuente original: https://github.com/buds-lab/building-data-genome-project-2

## Metodología
1. Exploración y limpieza de datos.
2. Análisis de consumo y temperatura.
3. Entrenamiento y comparación de modelos de regresión.
4. Selección de Random Forest.
5. Estimación de emisiones mediante CodeCarbon.
6. Evaluación de propuestas de eficiencia energética y energía solar.

## Resultados principales
- Random Forest: MAE de 1,88 kWh, RMSE de 3,67 kWh y R² de 0,9478.
- Consumo del edificio en 2017: 313.654,41 kWh.
- Simulación solar fotovoltaica de 40 kW: 61.717 kWh/año.
- Cobertura solar anual teórica: 19,68%.

## Ejecución
Abrir el archivo .ipynb en Google Colab y ejecutar las celdas en orden. Se requiere acceso a Internet para descargar los datos originales.

## Referencias
- Building Data Genome 2: https://github.com/buds-lab/building-data-genome-project-2
- PVWatts: https://pvwatts.nlr.gov/
- CodeCarbon: https://codecarbon.io/

## Limitaciones
Los datos eléctricos corresponden a un edificio real, pero las medidas de ahorro y la instalación fotovoltaica son propuestas no implementadas. Las emisiones del entrenamiento son estimaciones.# TPI-Tecnologia-Ambiente-Kevin-Lanatta_CLASS-5-
Predicción del consumo eléctrico y propuestas de eficiencia energética mediante IA

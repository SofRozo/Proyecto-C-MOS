# Proyecto C - LogistiCo: Optimización en Rutas Nacionales y Estrategia de Recarga

Este repositorio contiene la implementación de modelos de optimización logística nacional para la empresa **LogistiCo**, desarrollados en el marco del curso **ISIS-3302** de la Universidad de los Andes.

## Descripción del Proyecto

Se implementan modelos matemáticos en Pyomo para planificar rutas nacionales considerando:
- Capacidad de carga y autonomía de vehículos
- Estrategias de recarga de combustible
- Peajes con tarifas variables
- Restricciones de peso por municipio

## Estructura del Repositorio

- `data-cases/`: Datos de entrada para cada caso (base, caso2, caso3)
- `models/`: Modelos Pyomo modulares (CVRP, recarga, completo)
- `scripts/`: Scripts para ejecutar cada caso de estudio
- `utils/`: Funciones auxiliares (lectura, validación, visualización, verificación)
- `results/`: Visualizaciones, tablas y archivos `.csv` de verificación
- `documentation/`: Informes, modelado matemático primera etapa y final con análisis y resultados
- `main.py`: Script principal de ejecución
- `requirements.txt`: Dependencias del entorno
- `README.md`: Este archivo

## Requisitos

- Python 3.9+
- Pyomo
- pandas
- matplotlib
- 


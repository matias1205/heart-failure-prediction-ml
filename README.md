# heart-failure-prediction-ml

# Predicción de Enfermedades Cardíacas mediante Aprendizaje Automático

Este repositorio contiene el proyecto final del curso Inteligencia Artificial de la Pontificia Universidad Católica del Perú (PUCP), orientado a la predicción de enfermedad cardíaca mediante modelos de aprendizaje automático supervisado.

## Integrantes

- Sasha Daniela Guzmán Oré
- Angel Arturo Villavicencio Muñoz
- Matias Esteban Marrufo Zapata
- Sebastian Alejandro Morales Cayampe
- Leonardo Jaime Flores Vera

## Descripción del proyecto

El proyecto utiliza el dataset Heart Failure Prediction, compuesto por 918 registros y 11 variables clínicas. Se aplicaron técnicas de preprocesamiento, ingeniería de características, selección híbrida de variables, validación cruzada estratificada, ajuste de hiperparámetros y evaluación final sobre un conjunto de prueba reservado.

## Modelos evaluados

- Regresión Logística
- Support Vector Machine
- Random Forest
- K-Nearest Neighbors

## Principales resultados

El modelo con mejor desempeño global fue Regresión Logística, con una exactitud de 0.89 y 12 falsos negativos en el conjunto de prueba. Los resultados sugieren que la selección de variables tuvo mayor impacto que la complejidad del modelo.

## Estructura del repositorio

```text
data/
  heart.csv

notebooks/
  ProyectoG1_Heart_Failure.ipynb

figures/
  pipeline.png
  curvas_roc.png

report/
  Grupo1-TA-Final.pdf

```
## Requisitos

Para instalar las librerías necesarias, ejecutar:

```bash
pip install -r requirements.txt



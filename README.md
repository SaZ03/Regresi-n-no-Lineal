# Análisis del Tiempo de Entrega y su Relación con la Calificación
# Regresión no Lineal

Este proyecto consiste en analizar y modelar la relación entre el tiempo de entrega de actividades y la calificación obtenida, utilizando diferentes enfoques de regresión.  

Se trabajó con la base de datos **`A1.6 Tiempo de Entrega.csv`**, que contiene 432 observaciones correspondientes a entregas realizadas en la clase de **Sistemas Digitales en la Universidad de Monterrey** durante el semestre de **Otoño 2022**.  

## Variables

- **Tiempo:** Tiempo restante (en horas) para que se cerrara la bandeja de entrega.  
  - Ejemplo: un valor de `1` significa que la tarea se entregó el domingo a las 11:00 p.m., mientras que un valor de `48` significa que se entregó dos días antes.  
- **Calificación:** Calificación obtenida en la actividad, en una escala de 0 a 110 (variable objetivo).  

## Objetivo

El objetivo principal fue comprobar la hipótesis de que **entre más cerca de la hora límite se entrega la tarea, peor es la calificación obtenida**, comparando tres tipos de modelos no lineales:  
- Polinomial  
- Segmentado  
- KNN  

## Archivos del proyecto

- **Base de datos:** [`TiempoDeEntrega.csv`](TiempoDeEntrega.csv)  
- **Reporte en Jupyter Notebook:** [`Regresión no Lineal.ipynb`](Regresión no Lineal.ipynb)  
- **Reporte en HTML:** [`Regresión no Lineal.html`](Regresión no Lineal.html)  
- **Reporte en PDF:** [`Regresión no Lineal.pdf`](Regresión no Lineal.pdf)  

Sin embargo, el **modelo polinomial resulta más interpretable**, al mostrar una relación clara con un punto máximo.  
Por lo tanto, el modelo “mejor” depende de si se prioriza la **precisión** (KNN) o la **claridad en la explicación** (Polinomial).  

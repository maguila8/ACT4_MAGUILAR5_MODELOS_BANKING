# ACT4_MAGUILAR5_MODELOS_BANKING

Comparación de modelos NLP para clasificación de textos con el dataset BANKING77.

## Descripción del caso de uso
Se compararon modelos de procesamiento de lenguaje natural (NLP) para la clasificación automática de textos. El objetivo fue evaluar su capacidad para asignar una categoría a una consulta escrita, considerando tanto el rendimiento predictivo como la eficiencia computacional. 

Se utilizó el conjunto de datos **BANKING77** disponible en Hugging Face, que contiene consultas relacionadas con servicios bancarios clasificadas en 77 categorías de intención. Se evaluaron tres modelos: **DistilBERT**, **BERT** y **DistilRoBERTa**, en versiones entrenadas previamente para clasificar consultas bancarias. 

La evaluación se realizó sobre el conjunto de prueba (*test*) y consideró las métricas *accuracy*, *precision*, *recall* y *F1-score macro*. También se registraron el tiempo total de ejecución y la latencia media por texto para comparar la calidad de las predicciones y la velocidad de procesamiento de cada modelo.

## Estructura del Repositorio
- `ACT4_MAGUILAR5.ipynb`: Cuaderno de Google Colab con el código de experimentación y evaluación.
- `requirements.txt`: Dependencias y librerías necesarias.
- `resultados_modelos_banking77.csv`: Tabla con los resultados y métricas obtenidas.

## Cómo ejecutar
1. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt

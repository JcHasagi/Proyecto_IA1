![Banner del proyecto](assets/banner_proyecto.png)

# Breast Cancer Wisconsin: clasificación de tumores malignos y benignos

Proyecto de Inteligencia Artificial · Universidad Industrial de Santander (UIS)

## Integrantes

- Juan Camilo Arias Sarabia
- David Ricardo Martinez
- Juan Felipe Castellanos

## Objetivo

Clasificar tumores de mama como **malignos (M)** o **benignos (B)** a partir de 30 medidas numéricas del núcleo celular, y comprobar si esa diferencia aparece también en la estructura de los datos sin usar el diagnóstico.

El proyecto se desarrolló en tres etapas, todas incluidas en el notebook acumulativo:

1. **Exploración y limpieza:** revisión de nulos y duplicados, detección de atípicos con el rango intercuartílico y gráficos por variable.
2. **Aprendizaje supervisado:** Decision Tree, Random Forest, SVM y una red neuronal (MLP), con partición 80/20, curvas de aprendizaje y validación cruzada.
3. **Aprendizaje no supervisado:** escalado, reducción a 2 componentes con PCA, K-Means y DBSCAN, comparados con el diagnóstico real.

## Dataset

**Breast Cancer Wisconsin (Diagnostic)**: 569 registros, 30 variables numéricas y la columna `diagnosis` (M/B).

- Fuente: [kaggle.com/datasets/uciml/breast-cancer-wisconsin-data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Copia local: [`data/data.csv`](data/data.csv)

## Video

[Ver la presentación del proyecto en YouTube](https://www.youtube.com/watch?v=moRvaEiY46E)

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| [`Cancer_wisconsin.ipynb`](Cancer_wisconsin.ipynb) | Notebook acumulativo con las tres etapas |
| [`data/data.csv`](data/data.csv) | Dataset original |
| [`assets/banner_proyecto.png`](assets/banner_proyecto.png) | Banner del proyecto |
| [`diapositivas/Presentacion_proyecto_IA1_BreastCancerWisconsin.pdf`](diapositivas/Presentacion_proyecto_IA1_BreastCancerWisconsin.pdf) | Presentación del proyecto |

## Cómo ejecutarlo

Abre el notebook en Jupyter o en Google Colab. Si se ejecuta desde el repositorio, carga `data/data.csv`; si no encuentra el archivo, monta Google Drive.

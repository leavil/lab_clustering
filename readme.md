# 🧠 Trabajo Práctico: Clustering en Datos de Películas de Hollywood

## Introducción
Breve explicación del propósito del trabajo.
Contextualización dentro del curso de IA de la UPC.
Importancia del clustering para encontrar estructuras ocultas en datos no etiquetados.

## Carga y Exploración del Dataset
- Lectura del archivo `Hollywood films.csv`.
- Limpieza de datos: manejo de valores faltantes, tipos de datos, etc.
- Exploración inicial: estadísticas descriptivas y visualización (histogramas, distribuciones, correlaciones).

## Preprocesamiento
- Selección de variables numéricas relevantes para clustering (por ejemplo: presupuesto, ingresos, duración).
- Escalado de variables (`StandardScaler`).
- Reducción de dimensionalidad con PCA o t-SNE para visualización en 2D.

## Aplicación de Técnicas de Clustering

### 📌 K-Means
- Implementación con diferentes valores de k.
- Visualización de clusters en 2D.
- Evaluación con Silhouette Score.

### 📌 DBSCAN
- Pruebas con distintos valores de `eps` y `min_samples`.
- Visualización y detección de outliers.
- Discusión sobre la sensibilidad de los parámetros.

### 📌 Clustering Jerárquico
- Construcción de dendrogramas con distintos métodos de linkage (ward, average, complete).
- Análisis de corte para obtener clusters.
- Comparación con otras técnicas.

## Evaluación de Resultados
- Comparación de resultados entre técnicas con métricas internas (Silhouette).
- Discusión de la estructura de clases emergente:
  - ¿Qué características comparten las películas agrupadas?
  - ¿Hay patrones entre películas exitosas o de bajo rendimiento?
  - ¿Qué técnicas se adaptan mejor al tipo de datos?

## Preguntas Críticas Generadas
- ¿Qué implican los grupos encontrados respecto al mercado cinematográfico?
- ¿Cómo podría aplicarse este clustering a una recomendación automatizada?
- ¿Qué limitaciones tienen los métodos aplicados en este dominio?

## Conclusiones
- Resumen de hallazgos clave.
- Reflexión sobre el valor del clustering no supervisado.
- Posibles extensiones o mejoras al trabajo.

## 📦 Entregables
- Jupyter Notebook bien documentado, con explicaciones y visualizaciones.

# Comparación de Modelos de Clasificación, Regresión y Clustering

Evaluación comparativa de múltiples algoritmos de machine learning sobre tres datasets del repositorio UCI, cubriendo clasificación, regresión y clustering.

## Datasets (UCI)
- [Secondary Mushroom Dataset](https://archive.ics.uci.edu/dataset/848/secondary+mushroom+dataset) — clasificación
- [Abalone Dataset](https://archive.ics.uci.edu/dataset/1/abalone) — regresión
- [Gas Turbine CO and NOx Emission Dataset](https://archive.ics.uci.edu/dataset/551/gas+turbine+co+and+nox+emission+data+set) — clustering

## Qué hice

**Clasificación (Mushroom Dataset)**
- Comparé Regresión Logística, Árbol de Decisión, Random Forest y una red neuronal en PyTorch.
- Obtuve hasta **99.68% de accuracy** en test con Random Forest.

**Regresión (Abalone Dataset)**
- Evalué KNN, Regresión Lineal Múltiple y SVR para predecir la edad a partir de variables físicas.
- SVR alcanzó **R² test = 0.454** y **MAE test = 1.293**.

**Clustering (Gas Turbine Dataset)**
- Apliqué K-Means para identificar posibles regímenes operativos a partir de datos de emisiones.
- Realicé tratamiento de outliers previo al modelado.

## Tecnologías
`Python` · `scikit-learn` · `PyTorch` · `pandas` · `numpy` · `matplotlib`/`seaborn`

## Resultados clave
| Dataset | Tarea | Mejor modelo | Métrica |
|---|---|---|---|
| Mushroom | Clasificación | Random Forest | 99.68% accuracy |
| Abalone | Regresión | SVR | R² = 0.454, MAE = 1.293 |
| Gas Turbine | Clustering | K-Means | Regímenes operativos identificados |

## Estructura del repositorio

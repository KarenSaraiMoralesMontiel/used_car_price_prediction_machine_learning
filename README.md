# Proyecto Final: Modelo de Predicción de Vehículos Usados

## Objetivo general
Desarrollar un modelo de aprendizaje supervisado para la estimación de precios de vehículos usados de la base de datos usada en el reto KaggleX Skill Assessment Challenge 2024.


## Objetivos específicos

- Desarrollar modelos de regresión lineal clásico y una MLP.
- Evaluar el modelo de regresión lineal por medio de la métrica ECM.
- Comparar los modelos entrenados.

## Resultados

| Nombre                | Tiempo (segundos)      | Párametros                                                                                 | MSE_error  |
|-----------------------|-------------|-------------------------------------------------------------------------------------------|------------|
| KNeighborsRegressor   | 957.273622  | {'clf__algorithm': 'ball_tree', 'clf__leaf_size': 12, 'clf__n_neighbors': 20, 'clf__weights': 'uniform'} | 198361907  |
| RandomForestRegressor | 139.468629  | {'clf__max_depth': 20, 'clf__min_samples_split': 5}                                        | 207304527  |
| MLP                   | 119.181046  | ![imagen](https://github.com/user-attachments/assets/9b537cae-f6e5-4bba-8272-adf62330a3fa) | 226121647  |
| Linear Regression     | 0.0532186   | 1                                                                                         | 226915527  |
| DecisionTreeRegressor | 0.97377157  | {'clf__criterion': 'friedman_mse', 'clf__max_depth': None, 'clf__min_samples_split': 5}    | 232297417  |
| LogisticRegressor     | 2337.74438  | {'clf__C': 0.1, 'clf__penalty': 'l2'}                                                     | 307414507  |


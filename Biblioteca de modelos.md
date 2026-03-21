# Biblioteca de modelos

Como resultado de la práctica de modelos supervisados realizada en el segundo trimestre, a continuación se muestra la documentación que habéis generado para los diferentes modelos elegidos. Los he clasificado en tres categorías diferentes.
## Modelos paramétricos y estadísticos

![](https://i0.wp.com/spotintelligence.com/wp-content/uploads/2024/05/decision-boundaries-gaussian-naive-bayes.jpg?fit=1200%2C675&ssl=1&resize=1280%2C720)

Estos modelos asumen que los datos siguen una forma predeterminada (una línea o una distribución normal). Su objetivo es encontrar los **parámetros** ($\beta$, $\mu$, $\sigma$) que mejor describen esa forma. Se caracterizan por estar basados en funciones continuas y probabilidad, y son muy interpretables y rápidos, pero sufren si los datos no siguen la forma que el modelo espera.

- [Cell-Net con LogisticRegression - Josep Ramón](https://github.com/JoS153/Cell-Net-con-LogisticRegression/blob/main/CellNetDoc/DocumentacionCellNet.md)
- [Gaussian Naive Bayes - Sergio Fernández](https://github.com/ShearKs/Quinta-parte-de-documentaci-n-de-la-pr-ctica-Cell-Net-Evaluaci-n-de-modelos-/blob/main/README.md)
- [Quadratic Discriminant Analysis (QDA) - Jorge Sierra](https://github.com/jorgesierra89/QuadraticDiscriminantAnalysis/blob/main/README.md)
- [Regresión Logística - Daniel José Tercero](https://github.com/DanielMedac1/RegresionLogistica/blob/main/Regresi%C3%B3n%20Log%C3%ADstica.md)
- [Regresión Lineal - Lucas Barchín](https://github.com/lucasbm2/regresionlinealdocumentacion/blob/main/README.md)

## Algoritmos basados en árboles

![](https://machinelearningparatodos.com/wp-content/uploads/2023/06/decision_tree-1024x521.png)

Estos modelos dividen el espacio de datos en regiones jerárquicas mediante reglas lógicas en lugar de funciones globales. Al ser no paramétricos y combinar múltiples estimadores, capturan relaciones complejas y no lineales con gran robustez frente a valores atípicos. Su frontera de decisión es escalonada y se adapta con total flexibilidad a la estructura intrínseca de los datos sin asumir distribuciones previas.

- [Random Forest - Pablo Fernández](https://github.com/koalagordokbron/cell_net_evaluacion_modelos/blob/main/teorica/5ta_parte_PabloMorcillo.pdf)
- [Random Forest - David Horcajada](https://github.com/DavidHaRz/practica-comparacion-modelos/blob/main/README.md)
- [Random Forest - Alejandro Meneses](https://github.com/MenesesAlejandro93/Random-Forest/blob/main/README.md)
- [AdaBoost - Alejandro Simón](https://github.com/Alejandrosa0/AdaBoostClassifier/blob/main/README.md)
- [Evaluación de modelos multiclase - Raúl Moreno](https://github.com/Ra7x/Evaluacion-de-modelos-/blob/main/evaluacion_modelos_multiclase.ipynb)
- [Random Forest - Rossio Escalera](https://github.com/rossio-ai/RandomForest/blob/main/README.md)
- [Random Forest - Héctor Morales](https://github.com/hmoralesm01/explicationRandonForestClassifier/blob/main/GuiaUsoRandomForestClassifier.md)

## Otras arquitecturas de ensemble y redes neuronales

![](https://editor.analyticsvidhya.com/uploads/878490_sOtXk_8ZftGGU00_.png)

Agrupan arquitecturas complejas y sistemas de decisión colectiva que combinan múltiples predictores o capas de procesamiento. Son modelos de "caja negra" extremadamente potentes para tareas de alta dimensionalidad, aunque requieren mayor capacidad de cómputo. El Voting Classifier se caracteriza por optimizar el resultado mediante la "sabiduría de la mayoría" de otros modelos, mientras que las Redes Neuronales aprenden representaciones abstractas de los datos.

- [VotingClassifier - Sergio Roca](https://github.com/Sergiws/evaluacion_de_modelos/blob/main/README.md)
- [Red con Pytorch - Adrián Moreno](https://github.com/adrixennn/Explicacion_Modelo_CellNet_Pytorch/blob/main/README.md)

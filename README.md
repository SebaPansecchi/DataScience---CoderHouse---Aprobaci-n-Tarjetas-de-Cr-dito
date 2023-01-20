# 💳 Proyecto de clasificación de tarjetas de crédito
Este proyecto se enfoca en determinar si una solicitud de tarjeta de crédito debe ser aprobada o denegada,
utilizando un conjunto de datos sobre el nivel de atraso en el pago de tarjetas de crédito 
y datos estadíticos (estado civil, nivel de educación, categoría de ingresos) por parte de los clientes

# 📋 Requisitos
* Python 3.6 o superior
* Scikit-learn
* Seaborn
* Plotly 
* Pandas
* Numpy
* Mlxtend
* Imblearn

# 🚀 Proceso
1. Se recolecta y limpia la información de la base de datos.
2. Se realiza un análisis exploratorio de datos (EDA) y se plantean hipótesis.
3. Se divide la información en conjunto de entrenamiento y conjunto de prueba.
3. Se entrena el modelo de clasificación con el conjunto de entrenamiento optimizado.
4. Se evalúa el modelo con el conjunto de prueba optimizado.
5. Se utiliza el modelo entrenado para predecir la aprobación o rechazo de las solicitudes de tarjetas por parte de clientes

# 📊 Resultados
El modelo que mejores resultados arrojó fue el modelo de clasificación random forest de las siguientes características:

                       precision    recall  f1-score   support
                   0       0.84      0.86      0.85     16187
                   1       0.86      0.83      0.84     16190
                   2       0.99      1.00      0.99     16205
            accuracy                           0.90     48582
            macro avg      0.90      0.90      0.90     48582
            weighted avg   0.90      0.90      0.90     48582

# 📝 Notas
* El modelo actualmente utilizado es Random Forest, pero se pueden probar otros modelos modificando el código en "train_model.py".
* Para mayor detalle mirar 
* El conjunto de datos utilizado es solo para fines de demostración y no debe ser utilizado para tomar decisiones financieras reales.

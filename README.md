# Prediccion de precios de vuelos / Flight Price Prediction

Este proyecto se enfoca en predecir los precios de vuelos, comenzando con la preparación de datos para asegurarse de que todo esté listo para el modelado.

Utilicé One-Hot encoding para las columnas categóricas y ordinal encoding para la columna "stops" para manejar los datos adecuadamente.

Después de probar algunos modelos diferentes, el Random Forest Regressor resultó dar los mejores resultados, con un error (RMSE) de alrededor del 13%.

Inicialmente, hubo un alto sobreajuste, por lo que implementé RandomizedSearchCV para encontrar el mejor modelo.

Las características que más afectan el precio son la clase, que ayudó al modelo a hacer predicciones más precisas al centrarse en lo que más importa para los precios.

## English

This project focuses on predicting flight prices, starting with some data preparation to make sure everything’s ready for modeling.

I used One-Hot Encoding for the categorical columns and Ordinal Encoding for the "stops" column to handle the data properly. 

After trying out a few different models, Random Forest Regression turned out to give the best results, with an error (RMSE) of around 13%. 

Initially, there was a lot of overfitting, so I implemented RandomizedSearchCV to find the best model.

The features that most affect the price are class, which helped the model make more accurate predictions by focusing on what matters most for pricing.

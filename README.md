# Sentiment-vs-Emotion-Prediction--Tweets----ML-NLP-project

ESP:

Proyecto de entrenamiento supervisado de modelos de Machine Learning para predecir el sentimiento y la emoción de un tweet dado utilizando un dataset de casi 25.000 tweets y modelos de Scikit-Learn.

Entrenamos 2 modelos (sentimiento y emoción) para, finalmente, comparar la precisión de ambos y determinar cuál es más eficaz.

El dataset se obtuvo a través de Kaggle.

Se realizó la tokenización de las palabras, la eliminación de stopwords (tuvimos que añadir varias expreciones o slang), el filtrado de palabras que consideramos inútiles (eliminamos hashtags, etiquetados, palabras muy cortas, sin vocales, etc.), la creación de nuevas columnas utilizando los hashtags y las etiquetas así como también la polaridad y subjetividad, la separación en grupo de entrenamiento y de prueba, la comparación de los modelos a través de sus métricas, la validación y optimización (grid search) del mejor modelo de cada variable a predecir, y la visualización de las predicciones del grupo de prueba para entender mejor el resultado de las predicciones.

Este proyecto fue realizado en conjunto con Germán Fernández y Sergio Soler para el bootcamp de Data Science impartido por Hack A Boss. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

ENG:

Supervised Machine Learning Training Project to Predict Sentiment and Emotion of a given tweet using a dataset of nearly 25,000 tweets and Scikit-Learn models.

We trained 2 models (sentiment and emotion) to eventually compare the accuracy of both and determine which one is more effective.

The dataset was obtained through Kaggle.

We performed word tokenization, removal of stopwords (we had to add various expressions or slang), filtering out words we deemed useless (hashtags, mentions, very short words, vowel-less words, etc.), creation of new columns using hashtags and mentions as well as polarity and subjectivity, splitting into training and test sets, comparing the models through their metrics, validation and optimization (grid search) of the best model for each predictive variable, and visualization of predictions on the test set to better understand the prediction outcomes.

This project was carried out in collaboration with Germán Fernández and Sergio Soler for the Data Science bootcamp taught by Hack A Boss.

# HealthCostPredictor
Es uno de los proyectos del curso de Machine Learning con Python. Se nos proporciona un fichero .csv con datos sobre características de la personas: fumador, hijos, sexo, región residencia, y coste sanitario. Y se nos pide que elaboremos un previsor del coste sanitario futuro, como algoritmo de regresión. Hay que convertir los datos categorizados a números y examinar los datos en la tabla, para posteriormente crear un modelo de entrenamiento sobre los costes, diferenciando, la muestra de entrenamiento y la de testeo. Finalmente se evalúa el modelo con el test_dataset para ver su exactitud. Para superar la prueba, la media absoluta del error debe ser menor que 3500 dolares. Posteriormente visualizamos los gráficos  que predicen el coste sanitario futuro.

TEXTO EXPORTADO DE GOOGLE COLAB_

Note: You are currently reading this using Google Colaboratory which is a cloud-hosted version of Jupyter Notebook. This is a document containing both text cells for documentation and runnable code cells. If you are unfamiliar with Jupyter Notebook, watch this 3-minute introduction before starting this challenge: https://www.youtube.com/watch?v=inN8seMm7UI

In this challenge, you will predict healthcare costs using a regression algorithm.

You are given a dataset that contains information about different people including their healthcare costs. Use the data to predict healthcare costs based on new data.

The first two cells of this notebook import libraries and the data.

Make sure to convert categorical data to numbers. Use 80% of the data as the train_dataset and 20% of the data as the test_dataset.

pop off the "expenses" column from these datasets to create new datasets called train_labels and test_labels. Use these labels when training your model.

Create a model and train it with the train_dataset. Run the final cell in this notebook to check your model. The final cell will use the unseen test_dataset to check how well the model generalizes.

To pass the challenge, model.evaluate must return a Mean Absolute Error of under 3500. This means it predicts health care costs correctly within $3500.

The final cell will also predict expenses using the test_dataset and graph the results.

# TRAFFIC SIGN CLASSIFIER
[ES]
El objetivo de este proyecto es crear un modelo de aprendizaje profundo utilizando TensorFlow que pueda clasificar con precisión diferentes clases de señales de tráfico. Al aprovechar el poder de las CNN, buscamos desarrollar un modelo capaz de tomar decisiones más inteligentes en escenarios del mundo real, especialmente en el contexto de los vehículos autónomos.

Aquí tienes una descripción general de los pasos involucrados en la resolución de este problema de clasificación de señales de tráfico:

1. Adquisición de datos: Localizaremos y recopilaremos el conjunto de datos necesario para entrenar nuestro modelo. Este conjunto de datos incluirá varias imágenes de señales de tráfico con diferentes clases.
2. Preprocesamiento de datos: Antes de entrenar el modelo, debemos preprocesar las imágenes. Esto implica normalizar las imágenes, visualizar las diferentes clases, determinar sus dimensiones y redimensionarlas a un formato consistente.
3. Transformación de datos: Para realizar operaciones matemáticas en las imágenes, las convertiremos en matrices numéricas. Utilizaremos técnicas como codificación one-hot y normalización para preparar los datos para el entrenamiento.
4. Equilibrio de datos: Es crucial verificar si los datos están equilibrados o si existe un desequilibrio de clases. Abordaremos este problema si está presente para asegurar que el modelo se entrene de manera efectiva.
5. Arquitectura del modelo: Crearemos la arquitectura de nuestro modelo, específicamente una CNN. Esto implicará definir las capas, sus parámetros y las conexiones entre ellas.
6. Entrenamiento del modelo: Compilaremos el modelo, especificaremos la función de pérdida y el optimizador, y ajustaremos el modelo a los datos de entrenamiento. Esto implica ejecutar el modelo durante un número específico de épocas para mejorar su precisión y minimizar la pérdida.
7. Evaluación del modelo: Evaluaremos el rendimiento del modelo entrenado en un conjunto de datos de prueba separado. Esto nos ayudará a evaluar su precisión y capacidades de generalización.
8. Predicción y visualización: Utilizando el modelo entrenado, realizaremos predicciones sobre nuevos datos de prueba y compararemos las etiquetas originales con las predichas. Visualizaremos los resultados para obtener información sobre el rendimiento del modelo.

[EN]
The goal of this project is to create a deep learning model using TensorFlow that can accurately classify different classes of traffic signals. By harnessing the power of CNNs, we seek to develop a model capable of making smarter decisions in real-world scenarios, especially in the context of autonomous vehicles.

Here is an overview of the steps involved in solving this traffic signal classification problem:

1. Data acquisition: We will locate and collect the data set needed to train our model. This dataset will include several traffic sign images with different classes.
2. Data preprocessing: Before training the model, we must preprocess the images. This involves normalizing the images, visualizing the different classes, determining their dimensions and resizing them to a consistent format.
3. Data transformation: To perform mathematical operations on the images, we will convert them into numerical matrices. We will use techniques such as one-hot coding and normalization to prepare the data for training.
4. Data balancing: It is crucial to check if the data is balanced or if there is class imbalance. We will address this problem if it is present to ensure that the model is trained effectively.
5. Model architecture: We will create the architecture of our model, specifically a CNN. This will involve defining the layers, their parameters and the connections between them.
6. Model training: We will compile the model, specify the loss function and optimizer, and fit the model to the training data. This involves running the model for a specified number of epochs to improve its accuracy and minimize loss.
7. Model evaluation: We will evaluate the performance of the trained model on a separate test data set. This will help us evaluate its accuracy and generalization capabilities.
8. Prediction and visualization: Using the trained model, we will make predictions on new test data and compare the original labels with the predicted labels. We will visualize the results to obtain information about the performance of the model.

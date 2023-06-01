# Clasificador de 3 tipos de tumores cerebrales

# Analisis y evaluación
Para ver el analisís completo del trabajo realizado, lea el documento "Analisis y evaluación de modelos" que se encuentra en el directorio raiz

## Descarga de dataset
El dataset original proviene de https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?select=Training


## División del dataset en train y test, y aumento de datos dentro de train
- Prerrequisitos: Tener un dateset y las librerías que piden los códigos a ejecutar
- Dentro de la carpeta "codigos" se encuentra el notebook "DivideandAugmentation.ipynb", dentro del código se deberan cambiar las carpetas y direcciones correspondientes al dataset que deseas dividir y aumentar, así como las proporciones que deseas que tenga tu train y test. (Las secciones correspondientes a los cambios vienen dentro del código en forma de comentarios)


## Creación de modelos
- Prerrequisitos: Tener un dateset y las librerías que piden los códigos a ejecutar
- Dentro de la carpeta "codigos" se encuentra el notebook "TumorClasss.ipynb" en el se encuentra el código necesario para la creación y entrenamiento de los 3 modelos.

## Prueba modelos
- Prerrequisitos: Tener un modelo entrenado acorde al programa y las librerías que piden los códigos a ejecutar
- Para probar los modelos, dentro de la carpeta "codigos" se encuentra el notebook "PruebaModelo.ipynb" dentro de ese codigo se deben de seleccionar la imagen que quieres clasificar y el modelo que desas utilizar

### Nota: Todos los modelos ya entrenados se encuentran en la capeta "Modelos"




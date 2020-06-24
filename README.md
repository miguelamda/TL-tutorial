# TL-tutorial
Este es un tutorial de Transfer Learning.

## Propósito
Este tutorial de Transfer Learning y Fine Tuning con Keras pretende dar las pautas principales para emplear esta técnica en Deep Learning, con ejemplos en visión por computador (donde esta técnica está teniendo más éxito).

## Presentación

**Transfer Learning.pdf**: Presentación de conceptos y dos casos de estudio.

## Tutorial

**TransferLearning.ipynb**: En este tutorial se juega con el modelo InceptionV3, demostrando su potencial para aplicar transfer learning en el dataset Knifey-Spoony, y aplicando transfer learning y fine tuning sobre para entrenar un nuevo modelo que se ajuste al conjunto de datos.

## Ejercicios

Se disponen varios ejercicios: uno en el que se pide repetir el proceso con el modelo VGG16, y otro donde se pide aplicar la técnica con otro conjunto de datos, Honey Bees Pollen, de Kaggle.

## Uso en Google Colab

Ejecuta el siguiente código en una celda, una vez hayas abierto un notebook:

    import os
    work_dir = "/content/TL-tutorial/"
    if os.getcwd() != work_dir:
        !git clone https://github.com/miguelamda/TL-tutorial.git
    os.chdir(work_dir)

## Edición 2019

Si buscas la edición de 2019, puedes acceder al Tag v1.0 [aquí](https://github.com/miguelamda/TL-tutorial/tree/v1.0).

## License (MIT)

This tutorial is based on the [TensorFlow tutorial](https://github.com/Hvass-Labs/TensorFlow-Tutorials) of [Magnus Erik Hvass Pedersen](http://www.hvass-labs.org).

These tutorials and source-code are published under the [MIT License](https://github.com/Hvass-Labs/TensorFlow-Tutorials/blob/master/LICENSE) which allows very broad use for both academic and commercial purposes.

A few of the images used for demonstration purposes may be under copyright. These images are included under the "fair usage" laws.

You are very welcome to modify these tutorials and use them in your own projects.
Please keep a link to the [original repository](https://github.com/Hvass-Labs/TensorFlow-Tutorials).

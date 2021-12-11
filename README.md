# DL1

## **Carrera de especialización en Inteligencia Artificial (CEIA)**

## **Universidad de Buenos Aires (UBA)**

En este repositorio se encuentran los trabajos prácticos relacionados a la materia de Deep learning I de la CEIA.

Temario de la asignatura:

> **Clase 1:** 
> * Introducción a Deep learning.
> * Likelihood, loss functions, hidden units and output units.
> 
> **Clase 2:** 
> * Optimization.
> * Regularization.
> * Hyperparameter optimization.
> 
> **Clase 3:** 
> * Introducción a PyTorch.
> * PyTorch y redes neuronales.
> 
> **Clase 4:** 
> * Vectorized gradients.
> * Vectorized backpropagation.
> * Dropout, Initilization, Batch normalization y Momentum en PyTorch.
> 
> **Clase 5:** 
> * Convolutional Neural Networks (CNN).
> 
> **Clase 6:** 
> * Recurrent Neural Networks (RNN).
> * Attention layers.
> 
> **Clase 7:** 
> * Encoder-Decoder.
> * Autoencoder.
> * Representation learning.
> * Embeddings.
> * Transfer learning.
> * Generative Adversarial Networks (GAN).
> 
> **Clase 8:** Examen: End to End implementation ML problem with PyTorch and Scikit-learn
> ------------------------------------------------------------------------------------------

En este repositorio se encuentran algunos de los ejercicios de práctica de la materia:
1) Se realiza una implementación con numpy del algorítmo SGD para encontrar el mínimo de una función y(x).
<img src="https://github.com/AlexBarria/DL1/tree/main/SGD_gif.gif" width="255" height="225">
A esa implementación se le agregan momentos de primer y segundo órden para comparar la velocidad de convergencia de los tres casos.
<img src="https://github.com/AlexBarria/DL1/tree/main/SGD_COMPA.png" width="255" height="225">
2) Dado un determinado gráfo de cómputo de implementa diferenciación automática para enocntrar los valores de las derivadas. En este caso se utiliza PyTorch.
<img src="https://github.com/AlexBarria/DL1/tree/main/grafo.PNG" width="255" height="450">
3) Para abordar un problema de regresión, se crea un data-set sintético. Primero se soluciona el problema implementado un algorítmo mini-batch SGD similar al punto 1. Se agrega regularización.
Por último se implementa una RNA MLP con PyTorch, agregando batch normalization y dropout.

Es importante mencionar que el objetivo de estos ejercicios no es obtener un gran desempeño en las métricas de evaluación si no conocer los distintos algorítmos, aprender como funcionan internamente, comprender el método en que PyTorch trabaja con los gradientes y saber como implementar un loop de entrenamiento para deep learning haciendo uso de las mejores prácticas.

En base al siguiente material: 
[VGG16_ConvolutionalNets_Pytorch][https://colab.research.google.com/drive/1pQmA74TXH0jHqL4sxqibwrExvLHwjgvo?usp=sharing]

Se realizo lo siguiente:
1. **Entrenar y validar la red convolucional básica con CIFAR-10:**
    - El código define una red convolucional básica llamada `CIFARConvNet`.
    - Se entrena esta red utilizando el dataset CIFAR-10 y se valida su desempeño.
    - Los resultados (pérdida y precisión) se almacenan en las variables `train_losses`, `val_losses`, `train_accuracies` y `val_accuracies`.
    - Se grafican estos resultados utilizando las funciones `plot_training_history` y `evolution`.

2. **Realizar fine-tuning de VGG-16 con CIFAR-10:**
    - Se carga un modelo pre-entrenado VGG-16 utilizando `models.vgg16(weights=models.VGG16_Weights.IMAGENET1K_V1)`.
    - Se habilitan las actualizaciones de los parámetros del modelo para fine-tuning (`param.requires_grad = False`).
    - Se reemplaza el clasificador original de VGG-16 con uno nuevo (`CIFARClassifier`).
    - Se entrena el modelo con CIFAR-10 y se valida su desempeño.
    - Se grafican los resultados utilizando las funciones `plot_training_history` y `evolution`.

3. **Realizar un entrenamiento completo de VGG-16 con CIFAR-10:**
    - Esta parte se realiza de manera similar al fine-tuning, pero en lugar de solo actualizar los parámetros del clasificador, se actualizan todos los parámetros del modelo utilizando: `param.requires_grad = True`
    - Se entrena el modelo con CIFAR-10 y se valida su desempeño.
    - Se grafican los resultados utilizando las funciones `plot_training_history` y `evolution`.

## Análisis e Interpretación de los resultados

### Parte 1: Entrenar y validar la red convolucional básica

![[Pasted image 20250424132409.png]]

![[Pasted image 20250424132427.png]]

### **Parte 2:  Fine-tuning de la red pre-entrenada VGG-16 con CIFAR-10**
![[Pasted image 20250425140741.png]]

![[Pasted image 20250425140753.png]]
### **Parte 3: Entrenamiento completo de VGG-16 con CIFAR-10**
![[Pasted image 20250425134437.png]]

![[Pasted image 20250425134445.png]]
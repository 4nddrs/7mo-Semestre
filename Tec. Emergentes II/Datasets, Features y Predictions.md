
## **1. Dataset (Conjunto de Datos)**
Un **dataset** es una colección estructurada de datos utilizada para entrenar y evaluar modelos de Machine Learning. 

### **Tipos de Datasets**
- **Dataset de Entrenamiento (Training Data)**: Se usa para entrenar el modelo.
- **Dataset de Validación (Validation Data)**: Se usa para ajustar hiperparámetros y evitar sobreajuste (*overfitting*).
- **Dataset de Prueba (Testing Data)**: Evalúa el rendimiento del modelo con datos nunca antes vistos.

### **Ejemplo de un Dataset (Clasificación de Flores)**
| ID | Largo del Pétalo | Ancho del Pétalo | Tipo de Flor |
|----|----------------|----------------|-------------|
| 1  | 4.7 cm        | 1.4 cm         | Iris-setosa |
| 2  | 5.1 cm        | 1.5 cm         | Iris-versicolor |
| 3  | 6.0 cm        | 2.0 cm         | Iris-virginica |

En este ejemplo:
- Los valores numéricos son **features**.
- La última columna es la **etiqueta** o **objetivo** (*label*).

---

## **2. Features (Características)**
Las **features** son las variables o atributos que describen los datos dentro del dataset. Son la entrada del modelo de Machine Learning.

### **Tipos de Features**
- **Numéricas**: Ejemplo: "Edad", "Peso", "Ingresos".
- **Categóricas**: Ejemplo: "Color", "Tipo de Producto".
- **Binarias**: Ejemplo: "Sí/No", "Verdadero/Falso".

### **Ejemplo de Features en Predicción de Precios de Casas**
| ID | Tamaño (m²) | Número de Habitaciones | Ubicación | Precio (Objetivo) |
|----|------------|---------------------|-----------|----------------|
| 1  | 120        | 3                   | Centro    | $200,000       |
| 2  | 80         | 2                   | Suburbios | $150,000       |

En este caso:
- **Features**: Tamaño, Número de Habitaciones, Ubicación.
- **Objetivo a predecir**: Precio.

---

## **3. Predictions (Predicciones)**
Las **predictions** son los resultados generados por un modelo de Machine Learning cuando se le proporcionan nuevas **features** como entrada.

### **Ejemplo de Predicción**
Si entrenamos un modelo con datos de precios de casas y le damos una nueva casa con:
- Tamaño: 100 m²
- Habitaciones: 2
- Ubicación: Centro

El modelo podría predecir:
- **Precio Estimado**: $180,000

### **Tipos de Predicciones**
1. **Clasificación**: Predice una categoría. Ejemplo: "¿Es spam o no?".
2. **Regresión**: Predice un valor numérico. Ejemplo: "¿Cuánto costará una casa?".

---

## **Resumen**
| Concepto | Descripción |
|----------|------------|
| **Dataset** | Colección de datos utilizada para entrenar modelos. |
| **Features** | Atributos de los datos que sirven de entrada al modelo. |
| **Predictions** | Salida del modelo tras procesar las features. |


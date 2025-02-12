
El **Machine Learning** se divide en diferentes tipos de aprendizaje. Los más comunes son:

1. **Aprendizaje Supervisado**
2. **Aprendizaje No Supervisado**

## **1. Aprendizaje Supervisado**
El **aprendizaje supervisado** usa un dataset etiquetado, lo que significa que cada entrada tiene una salida esperada. El modelo aprende a mapear **features (entrada)** con **etiquetas (salida deseada)**.

### **Ejemplo: Clasificación de Emails (Spam/No Spam)**
| ID  | Contenido del Email   | Etiqueta |
| --- | --------------------- | -------- |
| 1   | "Gana dinero fácil"   | Spam     |
| 2   | "Reunión a las 10 AM" | No Spam  |
| 3   | "Oferta especial"     | Spam     |

El modelo aprende a identificar patrones en los emails etiquetados y luego predice si un nuevo email es spam o no.

### **Tipos de Aprendizaje Supervisado**
- **Clasificación**: Predice categorías (Ejemplo: "Gato o Perro").
- **Regresión**: Predice valores numéricos (Ejemplo: "Precio de una casa").

### **Ejemplo de Regresión**
Si el modelo recibe los siguientes datos:

| Tamaño de la Casa (m²) | Precio |
|----------------|--------|
| 80 | $150,000 |
| 120 | $200,000 |

Cuando recibe un nuevo dato (100 m²), puede predecir su precio basado en los ejemplos anteriores.

---

## **2. Aprendizaje No Supervisado**
El **aprendizaje no supervisado** trabaja con datos **sin etiquetas**, encontrando patrones o agrupaciones ocultas en los datos sin una salida esperada.

### **Ejemplo: Agrupación de Clientes (Clustering)**
Una empresa quiere segmentar a sus clientes según su comportamiento de compra sin saber de antemano las categorías. El algoritmo agrupará clientes con hábitos similares sin que haya una etiqueta predefinida.

### **Tipos de Aprendizaje No Supervisado**
- **Clustering**: Agrupa datos similares (Ejemplo: segmentación de clientes).
- **Reducción de Dimensionalidad**: Reduce la cantidad de variables manteniendo la información relevante (Ejemplo: PCA - Análisis de Componentes Principales).

### **Ejemplo de Clustering**
Un dataset con datos de clientes:

| Cliente | Edad | Compras Mensuales |
|---------|------|------------------|
| A       | 25   | 10               |
| B       | 40   | 2                |
| C       | 30   | 15               |

El algoritmo puede encontrar **grupos de clientes** sin etiquetas previas:
- Grupo 1: Clientes jóvenes con compras frecuentes.
- Grupo 2: Clientes mayores con compras ocasionales.

---

## **Comparación**
| Característica | Aprendizaje Supervisado | Aprendizaje No Supervisado |
|--------------|----------------------|----------------------|
| **Datos de entrada** | Etiquetados | No etiquetados |
| **Ejemplo de salida** | "Este email es Spam" | "Grupo 1 de clientes" |
| **Ejemplo de aplicación** | Clasificación de imágenes, predicción de precios | Agrupación de clientes, detección de anomalías |
| **Métodos principales** | Clasificación y Regresión | Clustering y Reducción de Dimensionalidad |

---

## **Conclusión**
- **Si tienes datos etiquetados y quieres predecir una salida específica → Usa Aprendizaje Supervisado**.
- **Si no tienes etiquetas y buscas patrones ocultos → Usa Aprendizaje No Supervisado**.


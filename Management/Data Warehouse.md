📌 **Diagrama del Data Warehouse (esquema estrella** 

### 📌 Tabla de Hechos: Ventas
| ID_Venta | Fecha     | ID_Producto | ID_Tienda | ID_Proveedor | Cantidad_Vendida | Precio_Venta |
|----------|----------|-------------|-----------|-------------|-----------------|--------------|
| 1        | 2025-03-31 | 101         | 1         | 201         | 5               | 50.00        |
| 2        | 2025-03-30 | 102         | 2         | 202         | 3               | 75.00        |

### 📌 Dimensión Tiempo
| ID_Fecha | Año  | Mes  | Día |
|----------|------|------|-----|
| 1        | 2025 | 03   | 31  |
| 2        | 2025 | 03   | 30  |

### 📌 Dimensión Tienda
| ID_Tienda | Nombre           | Ubicación       |
|-----------|------------------|----------------|
| 1         | Tienda A         | Ciudad X       |
| 2         | Tienda B         | Ciudad Y       |

### 📌 Dimensión Producto
| ID_Producto | Nombre        | Categoría   | Precio  |
|------------|--------------|------------|--------|
| 101        | Laptop X     | Tecnología | 500.00 |
| 102        | Teléfono Y   | Tecnología | 300.00 |

### 📌 Dimensión Proveedor
| ID_Proveedor | Nombre       | Contacto        |
|-------------|-------------|----------------|
| 201         | Proveedor A  | contacto@a.com |
| 202         | Proveedor B  | contacto@b.com |

## 📄 **Informe: Objetivo del Trabajo**

### 🎯 **Objetivo**

El objetivo de este trabajo es diseñar e implementar un Data Warehouse basado en el dataset **Retail Store Inventory Forecasting** para optimizar la toma de decisiones en la gestión de inventarios. Se aplicarán técnicas de análisis multidimensional y minería de datos para obtener información relevante sobre el rendimiento de productos, previsión de demanda y eficiencia de distribución.

### 🔍 **Alcance**

- Modelar un **Data Warehouse** con un esquema estrella.
    
- Analizar tendencias de ventas y demanda por producto, tienda y tiempo.
    
- Evaluar el rendimiento de proveedores y optimizar la reposición de stock.
    
- Implementar reportes y dashboards para la toma de decisiones.
### 📈 **Beneficios**

- **Optimización del inventario**, reduciendo costos y evitando sobrestock o desabastecimiento.
    
- **Mejora en la eficiencia de distribución** mediante la evaluación del rendimiento de los proveedores.
    
- **Toma de decisiones estratégicas basada en datos** sobre ventas y tendencias de consumo.
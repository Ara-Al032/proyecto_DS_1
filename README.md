---

# 📊 Análisis de Ventas para la Toma de Decisiones  
**Proyecto para identificar la tienda óptima para vender, basado en datos históricos de ventas.**

---

## 📌 Propósito  
Este proyecto analiza datos históricos de ventas de 4 tiendas para ayudar al Sr. Juan a decidir cuál es la mejor opción para vender su negocio. Los análisis incluyen:  
- Ingresos totales por tienda.  
- Categorías más y menos vendidas.  
- Calificaciones promedio de clientes.  
- Productos más y menos vendidos.  
- Costos de envío promedio.  

Los resultados se complementan con visualizaciones claras (gráficos de barras, dispersión y otros) para facilitar la interpretación de los datos.

---

## 📈 Características  
- **Análisis detallado**: Cálculo de métricas clave usando lógica pura de Python.  
- **Visualizaciones interactivas**: Gráficos generados con `matplotlib` para resaltar patrones y tendencias.  
- **Recomendación estratégica**: Justificación clara de la tienda recomendada para vender.  
- **Datos reales**: Basado en registros históricos de ventas (precios, categorías, calificaciones, costos de envío).  

---

## 🛠️ Requisitos  
- Python 3.x  
- Librerías:  
  - `pandas` (para cargar datos desde CSV).  
  - `matplotlib` (para gráficos).  
  - `csv` (para procesamiento básico de datos).  

Instala las dependencias con:  
```bash
pip install pandas matplotlib
```

---

## 🚀 Cómo Ejecutar el Proyecto  
1. **Clona el repositorio**:  
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
   cd tu-repo
   ```  

2. **Ejecuta el script principal**:  
   ```bash
   python analisis.py
   ```  
   Esto generará gráficos y mostrará los resultados en la consola.  

3. **Visualiza los gráficos**:  
   Los gráficos se mostrarán automáticamente al ejecutar el script.  


## 📋 Hallazgos Principales  
### 1. **Ingresos Totales**  
- **Tienda 1**: $1,150,880,400.0 (más alta).  
- **Tienda 4**: $1,038,375,700.0 (más baja).  

### 2. **Categorías Más Vendidas**  
- **Muebles** y **Electrónicos** lideran en todas las tiendas.  
- **Libros** e **Instrumentos musicales** son las categorías menos vendidas.  

### 3. **Calificaciones Promedio**  
- **Tienda 3**: 4.05 (más alta).  
- **Tienda 1**: 3.98 (más baja).  

### 4. **Productos Destacados**  
- **Tienda 1**: Microondas, TV LED UHD 4K (más vendidos).  
- **Tienda 4**: Cama box (más vendido).  

### 5. **Costo de Envío**  
- **Tienda 4**: $23,459.46 (más eficiente).  
- **Tienda 1**: $26,018.61 (menos eficiente).  

---

## ✅ Recomendación Final  
**Vender la Tienda 3** al Sr. Juan.  
**Justificación**:  
- Combina **altos ingresos** ($1,098,019,600.0), la **mejor calificación de clientes** (4.05) y un **costo de envío moderado** ($24,805.68).  
- Sus categorías más vendidas (Muebles, Electrónicos) están alineadas con la demanda del mercado.  

---

## 📝 Conclusión  
Este proyecto demuestra cómo el análisis de datos puede guiar decisiones estratégicas. Al evaluar múltiples factores (rentabilidad, satisfacción del cliente, eficiencia logística), se identifica a la **Tienda 3** como la opción más equilibrada y rentable para la venta.  


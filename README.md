# 📊 Análisis de Segmentación de Clientes (RFM)

Proyecto de análisis de datos enfocado en segmentar clientes a partir de su comportamiento de compra utilizando la metodología RFM (Recencia, Frecuencia y Valor Monetario).  
El objetivo es identificar distintos perfiles de clientes y entender cómo se distribuye el valor económico dentro del negocio.

---

## 📋 Descripción del problema
No todos los clientes aportan el mismo valor al negocio.  
Identificar cuáles son los más valiosos, cuáles son leales y cuáles están en riesgo es clave para diseñar estrategias efectivas de retención y crecimiento.

El reto consiste en analizar datos transaccionales y construir métricas que permitan segmentar a los clientes según su comportamiento.

---

## 🔄 Pipeline del análisis

Datos → Limpieza → EDA → Feature Engineering → Agregación por cliente → RFM → Segmentación → Análisis → Insights  

---

## 🔄 Pipeline de análisis de datos
Se desarrolló un proceso de análisis para transformar los datos transaccionales en métricas a nivel cliente y segmentarlos según su comportamiento:

| Etapa | Descripción |
|------|------------|
| Limpieza de datos | Corrección de tipos, manejo de valores nulos y duplicados |
| Análisis exploratorio (EDA) | Identificación de patrones en compras e ingresos |
| Ingeniería de características | Creación de la variable revenue |
| Agregación por cliente | Construcción de métricas como órdenes, ingresos y fechas |
| Cálculo de métricas RFM | Recencia, frecuencia e ingreso total por cliente |
| Segmentación | Clasificación de clientes según su comportamiento |
| Análisis | Evaluación de la distribución de ingresos y actividad |
| Insights | Interpretación de resultados |

---

## 📈 Resultados

### 🏆 Hallazgo principal
Un grupo reducido de clientes concentra la mayor parte de los ingresos, mientras que una proporción importante de usuarios se encuentra en riesgo de abandono.

### 📊 Métrica principal

| Métrica | Valor |
|--------|------|
| Segmento con mayor ingreso total | High Value |
| Segmento con mayor número de clientes | At Risk |

---

## 🔍 Insights clave

- Los clientes de alto valor generan una proporción desproporcionada de los ingresos totales  
- Existe un grupo considerable de clientes en riesgo que lleva tiempo sin realizar compras  
- Los clientes leales presentan alta frecuencia, pero no necesariamente el mayor ingreso total  
- El valor económico no depende únicamente del número de órdenes, sino del monto generado por cliente  

---

## 💡 Impacto

Este análisis permite:

- Identificar clientes de alto valor para enfocar estrategias comerciales  
- Detectar clientes en riesgo y priorizar acciones de retención  
- Comprender cómo se distribuyen los ingresos entre los clientes  
- Apoyar la toma de decisiones basada en comportamiento real de usuarios  

---

## 🛠️ Tecnologías utilizadas

- **Python** – lenguaje principal  
- **Pandas & NumPy** – procesamiento y manipulación de datos  
- **Matplotlib** – visualización de datos  
- **Seaborn** – visualización exploratoria  
- **Jupyter Notebook** – entorno de desarrollo  

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/angel-ayala2102/customer_behavior_analysis_retail.git
```

2. Instalar dependencias:
```bash
pip install -r requirements.txt
```

3. Abrir el notebook:
```bash
jupyter notebook Customer_Behavior_Analysis_Retail.ipynb
```

4. Ejecutar todas las celdas para reproducir el análisis  

---

## 🧑‍💻 Autor

**Ángel Luis Ayala Guzmán** – Data Analyst | Machine Learning & Customer Behavior  

🌐 [Portafolio](https://tu-portfolio.com) · [LinkedIn](https://www.linkedin.com/in/angel-luis-ayala) · ✉️ ayala.luis2102@gmail.com  

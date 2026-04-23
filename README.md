# 📊 Análisis de Segmentación de Clientes (RFM)

🇲🇽 Español | 🇺🇸 English

---

## 🇲🇽 Español

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

## 🇺🇸 English

Data analysis project focused on segmenting customers based on their purchasing behavior using the RFM methodology (Recency, Frequency, Monetary Value).  
The goal is to identify different customer profiles and understand how economic value is distributed within the business.

---

## 📋 Problem Description
Not all customers contribute the same value to the business.  
Identifying which ones are the most valuable, which are loyal, and which are at risk is key to designing effective retention and growth strategies.

The challenge is to analyze transactional data and build metrics that allow customer segmentation based on behavior.

---

## 🔄 Analysis Pipeline

Data → Cleaning → EDA → Feature Engineering → Customer Aggregation → RFM → Segmentation → Analysis → Insights  

---

## 🔄 Data Analysis Pipeline
A data analysis process was developed to transform transactional data into customer-level metrics and segment them based on behavior:

| Stage | Description |
|------|------------|
| Data cleaning | Data type correction and handling of missing and duplicate values |
| Exploratory Data Analysis (EDA) | Identification of patterns in purchases and revenue |
| Feature engineering | Creation of the revenue variable |
| Customer aggregation | Construction of metrics such as orders, revenue, and dates |
| RFM calculation | Recency, frequency, and total revenue per customer |
| Segmentation | Classification of customers based on behavior |
| Analysis | Evaluation of revenue distribution and activity |
| Insights | Interpretation of results |

---

## 📈 Results

### 🏆 Key Finding
A small group of customers generates the majority of total revenue, while a significant portion of users is at risk of churn.

### 📊 Main Metrics

| Metric | Value |
|--------|------|
| Segment with highest total revenue | High Value |
| Segment with largest number of customers | At Risk |

---

## 🔍 Key Insights

- High-value customers generate a disproportionate share of total revenue  
- There is a considerable group of at-risk customers who have not made purchases recently  
- Loyal customers show high frequency but not necessarily the highest total revenue  
- Economic value depends not only on order count but on revenue per customer  

---

## 💡 Impact

This analysis enables:

- Identification of high-value customers to guide business strategies  
- Detection of at-risk customers and prioritization of retention actions  
- Understanding of how revenue is distributed across customers  
- Data-driven decision-making based on real user behavior  

---

## 🛠️ Technologies Used

- **Python** – main programming language  
- **Pandas & NumPy** – data processing and manipulation  
- **Matplotlib** – data visualization  
- **Seaborn** – exploratory visualization  
- **Jupyter Notebook** – development environment  

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/angel-ayala2102/customer_behavior_analysis_retail.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook Customer_Behavior_Analysis_Retail.ipynb
```

4. Run all cells to reproduce the analysis  

---

## 🧑‍💻 Author

**Ángel Luis Ayala Guzmán** – Data Analyst | Machine Learning & Customer Behavior  

🌐 [Portfolio](https://angel-ayala-portfolio.my.canva.site/) · [LinkedIn](https://www.linkedin.com/in/angel-luis-ayala) · ✉️ angelluisayala21@gmail.com

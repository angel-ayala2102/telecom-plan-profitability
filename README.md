# 📊 Análisis de Rentabilidad de Planes de Telecomunicaciones

Proyecto de análisis de datos enfocado en evaluar la rentabilidad de planes de prepago en una empresa de telecomunicaciones.  
El objetivo es identificar qué plan genera mayores ingresos y entender el comportamiento de consumo de los usuarios.

---

## 📋 Descripción del problema
La empresa ofrece dos planes de prepago: **Surf** y **Ultimate**.  
Determinar cuál de los dos es más rentable es clave para optimizar la estrategia comercial y la asignación de presupuesto en marketing.

El reto consiste en analizar el comportamiento de los clientes y calcular los ingresos generados por cada plan utilizando datos históricos.

---

## 🔄 Pipeline del análisis

Datos → Limpieza → EDA → Feature Engineering → Integración → Cálculo de ingresos → Análisis → Validación → Insights

---

## 🔄 Pipeline de análisis de datos
Se desarrolló un proceso de análisis para preparar los datos, calcular ingresos y comparar el desempeño de los planes:

| Etapa | Descripción |
|------|------------|
| Limpieza de datos | Corrección de tipos, manejo de valores nulos |
| Análisis exploratorio (EDA) | Identificación de patrones de consumo |
| Ingeniería de características | Creación de variables como consumo mensual |
| Integración de datos | Unión de múltiples fuentes en un dataset consolidado |
| Cálculo de ingresos | Construcción de métricas de ingreso por usuario |
| Evaluación | Comparación entre planes mediante métricas y visualizaciones |
| Validación | Pruebas estadísticas para validar diferencias |
| Insights | Interpretación de resultados |

---

## 📈 Resultados

### 🏆 Hallazgo principal
El plan **Surf genera mayores ingresos totales**, mientras que el plan **Ultimate presenta mayor ingreso promedio por usuario**, pero con menor volumen de clientes.

### 📊 Métrica principal

| Métrica | Valor |
|--------|------|
| Ingreso promedio mensual (Surf) | 60.41 USD |
| Ingreso promedio mensual (Ultimate) | 72.25 USD |

---

## 🔍 Insights clave

- El plan Surf concentra mayor volumen de usuarios, lo que impulsa sus ingresos totales  
- Los usuarios del plan Surf tienden a generar más cargos por excedentes  
- El plan Ultimate presenta usuarios con mayor gasto promedio, pero menor participación total  
- Existen diferencias claras en los patrones de consumo entre ambos planes  

---

## 💡 Impacto

Este análisis permite:

- Identificar el plan más rentable para la empresa  
- Optimizar la asignación de presupuesto en marketing  
- Comprender el comportamiento de consumo de los usuarios  
- Detectar oportunidades para ajustar la estrategia de precios  

---

## 🛠️ Tecnologías utilizadas

- **Python** – lenguaje principal  
- **Pandas & NumPy** – procesamiento y manipulación de datos  
- **Matplotlib** – visualización de datos  
- **SciPy** – pruebas estadísticas  
- **Jupyter Notebook** – entorno de desarrollo  

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:
git clone https://github.com/angel-ayala2102/telecom-plan-profitability.git

2. Instalar dependencias:
pip install -r requirements.txt

3. Abrir el notebook:
jupyter notebook telecom_plan_profitability.ipynb

4. Ejecutar todas las celdas para reproducir el análisis

---

## 🧑‍💻 Autor

**Ángel Luis Ayala Guzmán** – Data Analyst | Machine Learning & Customer Behavior

🌐 [Portafolio](https://tu-portfolio.com) · [LinkedIn](https://www.linkedin.com/in/angel-luis-ayala) · ✉️ ayala.luis2102@gmail.com

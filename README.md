📊 Telecom X - Análisis de Churn de Clientes
Repositorio del proyecto de análisis de datos para identificar factores de abandono de clientes en Telecom X.

📌 Descripción del Proyecto
Este proyecto analiza los datos de clientes de Telecom X para identificar patrones y predictores clave del churn (abandono de clientes). El objetivo es proporcionar insights accionables que permitan reducir la tasa de evasión y mejorar las estrategias de retención.

Problema:

Telecom X enfrenta una alta tasa de cancelaciones, afectando su rentabilidad.

Solución:

Análisis exploratorio (EDA) y visualización de datos.

Identificación de segmentos críticos.

Recomendaciones basadas en datos.

📂 Estructura del Repositorio
text
telecom-churn-analysis/  
├── data/  
│   └── TelecomX_diccionario.md        # Diccionario de datos
     └── TelecomX_Data.json            # Dataset original (JSON)  
├── notebooks/  
│   └── TelecomX_Churn_Analysis.ipynb # Jupyter Notebook con el análisis completo  
├── │   └── Informe_Churn_TelecomX   # Reporte ejecutivo 
├── README.md                         # Este archivo  

🔍 Análisis Realizado
1. Limpieza y Preparación de Datos
Normalización de datos anidados (JSON → DataFrame).

Tratamiento de valores nulos y duplicados.

Creación de nuevas variables (ej: Cuentas_Diarias).

2. Análisis Exploratorio (EDA)
Distribución de churn por:

Factores demográficos (género, edad).

Tipo de contrato (mes a mes, anual, bianual).

Servicios (fibra óptica, TV, soporte técnico).

Métodos de pago.

Correlación entre antigüedad (tenure) y cargos totales.

3. Visualizaciones Clave
Gráficos de barras agrupadas (churn por categorías).

Histogramas y boxplots (distribución de cargos).

Scatter plots (relación tenure vs. gasto).

🚀 Resultados Destacados
🔴 Factores de Alto Riesgo
Contratos mensuales: 42.7% de tasa de churn.

Fibra óptica: 41% de abandonos.

Pago por e-check: 34% de churn.

🟢 Factores Protectores
Contratos bianuales.

Clientes con tenure >24 meses..

🛠️ Requisitos Técnicos
Dependencias
bash
pip install -r requirements.txt
Contenido de requirements.txt:

Clonar repositorio:

bash
git clone https://github.com/ingchavo/telecom-churn-analysis.git
Abrir Jupyter Notebook:

bash
jupyter notebook notebooks/TelecomX_Churn_Analysis.ipynb

📝 Licencia
Este proyecto está bajo licencia MIT.

📬 Contacto
¿Preguntas o colaboraciones?
✉️ ingchavo@gmail.com

🔗 Acceso al Dataset: GitHub Raw
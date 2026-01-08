# 📊 Telecom X - Análisis de Evasión de Clientes (Churn Analysis)

## 📋 Descripción del Proyecto

Este proyecto consiste en un análisis completo de datos para **Telecom X**, una empresa de telecomunicaciones que enfrenta una alta tasa de cancelación de servicios por parte de sus clientes (fenómeno conocido como "Churn"). El objetivo principal es identificar los factores que influyen en la decisión de los clientes de abandonar el servicio y proporcionar recomendaciones estratégicas para mejorar la retención.

## 🎯 Objetivos

- **Identificar patrones** en el comportamiento de clientes que abandonan
- **Analizar factores demográficos** y de servicio asociados al churn
- **Desarrollar estrategias** basadas en datos para reducir la evasión
- **Crear visualizaciones** informativas para comunicar hallazgos clave

## 📁 Estructura del Proyecto

## 🔧 Tecnologías Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Cálculos numéricos
- **Matplotlib & Seaborn** - Visualización de datos
- **Jupyter Notebook** - Ambiente de análisis interactivo
- **Plotly** (opcional) - Visualizaciones interactivas

## 📊 Dataset

### Variables Principales
- **customerID**: Identificador único del cliente
- **Churn**: Variable objetivo (0=No abandonó, 1=Sí abandonó, 2=No responde)
- **Datos demográficos**: gender, SeniorCitizen, Partner, Dependents
- **Servicios**: PhoneService, InternetService, MultipleLines, OnlineSecurity, etc.
- **Contrato y facturación**: Contract, PaperlessBilling, PaymentMethod
- **Métricas financieras**: tenure, Charges.Monthly, Charges.Total, Cuentas_Diarias

### Procesamiento de Datos
1. **Extracción**: Carga de datos JSON con estructura anidada
2. **Normalización**: Transformación de datos anidados a formato tabular
3. **Limpieza**: Verificación de valores nulos y duplicados
4. **Transformación**: Conversión de variables categóricas a numéricas
5. **Feature engineering**: Creación de variable "Cuentas_Diarias"

## 📈 Hallazgos Principales

### 🔴 Factores de Alto Riesgo
1. **Contrato mensual**: 47.8% de tasa de abandono
2. **Pago por cheque electrónico**: 50.3% de tasa de abandono
3. **Servicio de fibra óptica**: 46.9% de tasa de abandono

### 📊 Métricas Clave
- **Tasa de abandono general**: 26.5%
- **Clientes analizados**: 7,267
- **Clientes que abandonaron**: 1,869
- **Clientes retenidos**: 5,174

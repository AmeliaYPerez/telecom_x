
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

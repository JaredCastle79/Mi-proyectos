# Análisis de Retención de Clientes para Model Fitness 🏋️‍♂️📊
# Descripción del Proyecto
Este proyecto analiza datos de clientes de Model Fitness, una cadena de gimnasios, para predecir la pérdida de clientes (churn) y desarrollar estrategias de retención. El objetivo es identificar patrones de comportamiento, segmentar a los usuarios y proponer acciones que reduzcan la rotación.

# Objetivos Principales
Predecir la probabilidad de abandono de cada cliente en el próximo mes.
Segmentar a los clientes en grupos con características similares.
Identificar factores clave que influyen en la cancelación de membresías.
Proponer recomendaciones personalizadas para mejorar la retención.

# Metodología
Análisis Exploratorio de Datos (EDA): Visualización de distribuciones, correlaciones y diferencias entre clientes que se quedan y los que abandonan.
Modelado Predictivo:
Regresión Logística.
Bosques Aleatorios (Random Forest).

# Clustering:
Agrupamiento jerárquico (dendrograma).
K-Means para identificar perfiles de clientes (n=5 clústeres).
Evaluación de Métricas: Exactitud, precisión y recall para comparar modelos.

# Dataset
El dataset contiene información histórica de clientes, incluyendo:
Datos demográficos (género, edad, cercanía al gimnasio).
Comportamiento de visitas (frecuencia, sesiones grupales).
Detalles de contratos (duración, meses restantes).
Historial de gastos adicionales (cafetería, productos, etc.).

# Hallazgos Clave
Factores de alto impacto en el churn: Baja frecuencia de visitas, contrato próximo a expirar, menor interacción con servicios adicionales.
Segmentos críticos: Clientes con membresías cortas (1 mes) y aquellos que no viven cerca del gimnasio.

# Recomendaciones:
Ofrecer incentivos a clientes con contratos próximos a vencer.
Programas de fidelización para segmentos de alto riesgo.
Promover sesiones grupales para aumentar engagement.

# Tecnologías Utilizadas
Python (Pandas, NumPy, Matplotlib/Seaborn).
Scikit-learn (Regresión Logística, Random Forest, K-Means).
SciPy (agrupamiento jerárquico).

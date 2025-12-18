# Analisis-y-Clasificacion-de-clientes-mediante-clustering
Segmentación de clientes usando PCA y K-Means para identificar perfiles basados en edad, ingresos y gastos. El fin es crear estrategias de marketing personalizadas y optimizar decisiones comerciales según el comportamiento financiero real detectado en los datos.
Este proyecto aplica técnicas de aprendizaje no supervisado para segmentar la base de clientes de una organización basándose en su comportamiento financiero y características demográficas. El propósito es transformar datos brutos en perfiles accionables que permitan optimizar las campañas de comunicación y las decisiones de negocio.

Objetivos del Proyecto
Realizar un análisis exploratorio de datos sobre el comportamiento de compra de los usuarios.

Reducir la complejidad dimensional mediante el Análisis de Componentes Principales (PCA).

Identificar clústeres de comportamiento utilizando el algoritmo K-Means.

Desarrollar propuestas estratégicas de negocio fundamentadas en los segmentos detectados.

Metodología
El flujo de trabajo implementado en el notebook se divide en las siguientes etapas:

Preprocesamiento: Limpieza de datos y escalado mediante MinMaxScaler para normalizar las variables de Edad, Ingresos Anuales y Puntuación de Gasto.

Reducción de Dimensiones (PCA): Transformación de las variables originales en componentes principales para facilitar la visualización en un plano bidimensional sin perder varianza significativa.

Clustering con K-Means: Aplicación del algoritmo para agrupar a los clientes en 5 segmentos distintos, validados mediante el método del codo y el análisis de silueta.

Clustering Jerárquico: Validación de la estructura y cohesión de los grupos mediante dendrogramas.

Segmentos Identificados
A través del análisis se definieron los siguientes cinco perfiles estratégicos:

VIP: Altos ingresos y alta puntuación de gasto. Clientes de máxima rentabilidad y prioridad.

Ahorradores: Ingresos elevados con gasto conservador. Representan una oportunidad de crecimiento mediante productos de inversión o alta calidad.

Impulsivos: Ingresos moderados o bajos con alta disposición al gasto. Sensibles a tendencias y novedades.

Promedio: Comportamiento equilibrado en todas las variables. Constituyen la base estable del volumen de ventas.

Austeros: Ingresos y gastos bajos. Perfil orientado a la necesidad básica y alta sensibilidad al precio.

Tecnologías Utilizadas
Python 3.13

Pandas y NumPy: Procesamiento y manipulación de estructuras de datos.

Scikit-Learn: Implementación de escalado, reducción de dimensiones y algoritmos de clustering.

Matplotlib y Seaborn: Generación de visualizaciones estadísticas y gráficos de dispersión.

Jupyter Notebook: Entorno de desarrollo para la ejecución de código y documentación técnica.

Instrucciones de Uso
Descargue los archivos del repositorio.

Asegúrese de contar con el conjunto de datos datos_clientes.csv en el directorio raíz del proyecto.

Instale las librerías necesarias mediante el siguiente comando: pip install pandas scikit-learn matplotlib seaborn

Ejecute el notebook Proyecto del Día 12 - Análisis y Clasificación de Clientes Gian.ipynb para visualizar el proceso completo.

Conclusiones de Negocio
La implementación de este modelo de segmentación permite transitar de un marketing genérico a una estrategia de hiper-personalización. Al determinar que la edad y el poder adquisitivo son los motores principales del consumo, la empresa puede reducir el costo de adquisición de clientes y aumentar el valor del tiempo de vida del cliente mediante ofertas alineadas con el perfil financiero real.

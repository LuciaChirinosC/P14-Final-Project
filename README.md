# P14-Final-Project
📊 Proyecto Final – Bootcamp de Análisis de Datos
Telecomunicaciones, E-commerce y SQL Analytics
🧩 Descripción general

Este proyecto integra todos los conocimientos adquiridos durante el bootcamp, aplicados a tres casos de uso independientes que simulan tareas reales de un analista de datos junior.
El objetivo es diagnosticar, analizar y comunicar hallazgos basados en datos reales, entregando soluciones comprensibles tanto para equipos técnicos como de negocio.

## 🧠 Objetivos generales

- Aplicar habilidades técnicas: limpieza, análisis exploratorio, pruebas estadísticas, visualización y SQL.

- Aplicar habilidades estratégicas: storytelling, pensamiento crítico y comunicación de resultados.

- Desarrollar entregables profesionales que permitan la toma de decisiones basada en datos.

## 📁 Estructura del proyecto

El proyecto se divide en tres casos independientes:

### 🧩Caso 1: Telecomunicaciones CallMeMaybe – Identificación de operadores ineficaces 

Cliente: CallMeMaybe (servicio de telefonía virtual).
Objetivo: identificar operadores ineficaces con base en métricas de desempeño: llamadas perdidas, duración y volumen de llamadas.

Tareas principales:

- Limpieza y análisis exploratorio de los datasets telecom_dataset_us.csv y telecom_clients_us.csv.

- Identificación de patrones de ineficacia operativa.

- Comprobación de hipótesis estadísticas para validar los hallazgos.

- Creación de un dashboard en Tableau para la visualización de métricas clave.

Herramientas y justificación:

- Python (Pandas, NumPy): limpieza, manipulación y análisis exploratorio.

- Matplotlib / Seaborn: visualizaciones para distribución y correlaciones.

- Tableau Public: construcción de dashboard interactivo con filtros y KPIs.

Entregables:

- Dashboard interactivo (Tableau Public): Visualización dinámica de métricas clave (llamadas entrantes/salientes, duración, llamadas perdidas, tiempo de espera, rendimiento por operador).Permite a los supervisores identificar operadores ineficaces de forma inmediata.

- Informe analítico (.pdf): Documento con resumen ejecutivo, análisis estadístico, conclusiones y recomendaciones prácticas.

- Notebook de análisis (.ipynb): Código documentado y reproducible para auditoría técnica o seguimiento posterior.

### 🧪 Caso 2: E-commerce – Evaluación de una Prueba A/B

Cliente: Tienda en línea internacional (UE).
Objetivo: evaluar el impacto de un nuevo sistema de recomendaciones sobre el embudo de conversión.

Tareas principales:

- Revisión y validación de la integridad de datos de prueba A/B.

- Análisis exploratorio del comportamiento de usuarios (eventos product_page, product_card, purchase).

- Evaluación estadística de diferencias entre grupos mediante pruebas z de proporciones.

- Generación de conclusiones accionables sobre el rendimiento del nuevo sistema.

Herramientas y justificación:

- Python (Pandas, SciPy, Statsmodels): análisis estadístico y validación de hipótesis.

- Matplotlib / Plotly: visualización de tasas de conversión.

- Excel / Tableau: resumen de resultados para presentación ejecutiva.

Entregables:

- Informe de resultados (.pdf):Presentación clara de la validez del experimento, diferencias entre grupos y conclusiones con soporte estadístico (prueba z de proporciones).

- Visualizaciones comparativas (PowerPoint o Tableau):Gráficos de conversión y embudo de ventas, diseñados para la presentación ejecutiva.

- Notebook técnico (.ipynb):Análisis detallado de datos, tratamiento de duplicados, control de fechas y pruebas estadísticas implementadas en Python.


### 📚 Caso 3: SQL – Análisis de Base de Datos de Libros

Cliente: Startup del sector editorial digital.
Objetivo: generar una propuesta de valor basada en el análisis de datos de libros, autores y reseñas.

Tareas principales:

- Conectarse a la base de datos relacional del cliente.

- Ejecutar consultas SQL para obtener:

- Libros publicados después del 1/01/2000.

- Número de reseñas y calificaciones promedio por libro.

- Editorial con más publicaciones (>50 páginas).

- Autor con mejor calificación promedio (≥50 reseñas).

- Promedio de reseñas de texto entre usuarios activos.

- Documentar y presentar los hallazgos.

Herramientas y justificación:

- SQL: consultas analíticas en PostgreSQL.

- Pandas: lectura e interpretación de resultados.

- Jupyter Notebook: documentación estructurada del proceso.

Entregables para el cliente:

- Notebook de consultas SQL (.ipynb):Consultas ejecutadas y explicadas paso a paso, con resultados tabulares.

- Resumen analítico (.pdf): Recomendaciones basadas en los resultados: autores más rentables, editoriales destacadas y oportunidades de mercado.

- Exportación de resultados (.csv):Archivos con tablas filtradas y resultados principales, listos para integrar en otros sistemas o dashboards.

## 🛠️ Metodología de trabajo

El proyecto se desarrolla siguiendo un flujo completo: primero entendemos el problema y definimos los indicadores clave del cliente; luego preparamos y limpiamos los datos para asegurar su calidad. Después realizamos un análisis exploratorio para identificar patrones, relaciones y valores atípicos, aplicamos pruebas estadísticas según el caso, y creamos dashboards en Tableau para visualizar los resultados de manera clara. Finalmente, comunicamos los hallazgos mediante presentaciones en PDF y un resumen ejecutivo fácil de entender para el cliente.

## 🎯 Producto final

3 notebooks analíticos (uno por caso).

Dashboard interactivo (Tableau Public).

Presentación ejecutiva en PDF (storytelling con resultados, hipótesis y recomendaciones).

## 📚 Fuentes consultadas

- Pandas Documentation – Para limpieza, manipulación y transformación de los datasets.

- Matplotlib y Seaborn – Para generar visualizaciones y explorar distribuciones y correlaciones.

- SciPy.stats Documentation – Para aplicar pruebas estadísticas (pruebas z y de proporciones) en la prueba A/B.

- Tableau Public Guide – Para diseñar dashboards interactivos y filtrables según indicadores clave.

- PostgreSQL Documentation – Para consultas SQL y extracción de información de la base de datos relacional.

## Formatos y medios de entrega

- 📊 Dashboard: publicado en Tableau Public, con enlace compartido en dashboard.txt.

- 📘 Presentaciones: elaboradas en PowerPoint y exportadas a PDF para entrega formal.

- 💻 Código y análisis: desarrollado en Jupyter Notebook (.ipynb) con comentarios, estructura modular y resultados reproducibles.

- 📂 Archivos de respaldo: datasets procesados, tablas resumidas y gráficos exportados a formato .csv o .png según corresponda.

## 📬 Comunicación con el cliente
Durante el desarrollo del proyecto, mantendré una comunicación constante con el cliente para garantizar que los objetivos del análisis se cumplan y los resultados sean claros y accionables. La información será presentada en diferentes formatos, adaptados a las necesidades de los equipos técnicos y de negocio.

- Reunión inicial: definición de objetivos, KPIs e indicadores de rendimiento esperados.

- Revisión intermedia: presentación de avances y validación de enfoque analítico.

- Entrega final: exposición ejecutiva de resultados, hallazgos y recomendaciones en PDF y dashboard.

- Feedback post-entrega: reunión breve para resolver dudas o sugerencias sobre los análisis.

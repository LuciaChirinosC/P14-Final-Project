# P14-Final-Proyect
📊 Proyecto Final – Bootcamp de Análisis de Datos
Telecomunicaciones, E-commerce y SQL Analytics
🧩 Descripción general

Este proyecto integra todos los conocimientos adquiridos durante el bootcamp, aplicados a tres casos de uso independientes que simulan tareas reales de un analista de datos junior.
El objetivo es diagnosticar, analizar y comunicar hallazgos basados en datos reales, entregando soluciones comprensibles tanto para equipos técnicos como de negocio.

## 🧠 Objetivos generales

Aplicar habilidades técnicas: limpieza, análisis exploratorio, pruebas estadísticas, visualización y SQL.

Aplicar habilidades estratégicas: storytelling, pensamiento crítico y comunicación de resultados.

Desarrollar entregables profesionales que permitan la toma de decisiones basada en datos.

## 📁 Estructura del proyecto

El proyecto se divide en tres casos independientes:

### Caso 1: Telecomunicaciones – Identificación de operadores ineficaces

Cliente: CallMeMaybe (servicio de telefonía virtual).
Objetivo: identificar operadores ineficaces con base en métricas de desempeño: llamadas perdidas, duración y volumen de llamadas.

Tareas principales:

Limpieza y análisis exploratorio de los datasets telecom_dataset_us.csv y telecom_clients_us.csv.

Identificación de patrones de ineficacia operativa.

Comprobación de hipótesis estadísticas para validar los hallazgos.

Creación de un dashboard en Tableau para la visualización de métricas clave.

Herramientas y justificación:

Python (Pandas, NumPy): limpieza, manipulación y análisis exploratorio.

Matplotlib / Seaborn: visualizaciones para distribución y correlaciones.

Tableau Public: construcción de dashboard interactivo con filtros y KPIs.

SQLAlchemy: conexión a base de datos para validar consultas y análisis relacional.

Excel: validación cruzada de indicadores y preparación de datos para visualización.

Entregables:

Notebook de análisis (telecom_analysis.ipynb)

Dashboard interactivo en Tableau (dashboard.txt con link)

Conclusiones y recomendaciones para la dirección técnica

### Caso 2: E-commerce – Evaluación de una Prueba A/B

Cliente: Tienda en línea internacional (UE).
Objetivo: evaluar el impacto de un nuevo sistema de recomendaciones sobre el embudo de conversión.

Tareas principales:

Revisión y validación de la integridad de datos de prueba A/B.

Análisis exploratorio del comportamiento de usuarios (eventos product_page, product_card, purchase).

Evaluación estadística de diferencias entre grupos mediante pruebas z de proporciones.

Generación de conclusiones accionables sobre el rendimiento del nuevo sistema.

Herramientas y justificación:

Python (Pandas, SciPy, Statsmodels): análisis estadístico y validación de hipótesis.

Matplotlib / Plotly: visualización de tasas de conversión.

Excel / Tableau: resumen de resultados para presentación ejecutiva.

Entregables:

Notebook de análisis (ab_test_analysis.ipynb)

Gráficos comparativos de conversión por etapa

Informe con conclusiones y decisiones recomendadas

### Caso 3: SQL – Análisis de Base de Datos de Libros

Cliente: Startup del sector editorial digital.
Objetivo: generar una propuesta de valor basada en el análisis de datos de libros, autores y reseñas.

Tareas principales:

Conectarse a la base de datos relacional del cliente.

Ejecutar consultas SQL para obtener:

Libros publicados después del 1/01/2000.

Número de reseñas y calificaciones promedio por libro.

Editorial con más publicaciones (>50 páginas).

Autor con mejor calificación promedio (≥50 reseñas).

Promedio de reseñas de texto entre usuarios activos.

Documentar y presentar los hallazgos.

Herramientas y justificación:

SQL: consultas analíticas en PostgreSQL.

Pandas: lectura e interpretación de resultados.

Jupyter Notebook: documentación estructurada del proceso.

Entregables:

Notebook de consultas SQL (sql_analysis.ipynb)

Resultados de consultas y visualización de datos relevantes

Recomendaciones para estrategia de producto

## 🛠️ Metodología de trabajo

Definición del problema y objetivos.
Se analizan los requerimientos del cliente y se definen los indicadores clave de desempeño.

Preparación y limpieza de datos.
Tratamiento de valores nulos, duplicados y tipos de datos.

Análisis exploratorio y visualización.
Identificación de patrones, outliers y correlaciones relevantes.

Validación estadística e inferencia.
Aplicación de pruebas z, t y proporciones según el caso.

Desarrollo de dashboards e interpretación.
Visualización de resultados clave en Tableau.

Comunicación de resultados.
Elaboración de presentación en PDF y resumen ejecutivo para clientes.

## 🎯 Producto final

3 notebooks analíticos (uno por caso).

Dashboard interactivo (Tableau Public).

Presentación ejecutiva en PDF (storytelling con resultados, hipótesis y recomendaciones).

## 📚 Fuentes consultadas

Documentación oficial de Pandas – Limpieza y manipulación de datos.

Matplotlib y Seaborn – Técnicas de visualización profesional.

Artículo de Medium: “How to identify inefficient call center operators with data analytics”.

Guía de Tableau Public – Creación de dashboards interactivos con filtros.

Docs de SciPy.stats – Pruebas z de diferencia de proporciones.

PostgreSQL Docs – Consultas relacionales y funciones agregadas.

Tutorial de TripleTen sobre A/B Testing Workflow.

Curso de Kaggle sobre Data Cleaning and Feature Understanding.

## 📬 Comunicación con el cliente y entregables finales

Durante el desarrollo del proyecto, mantendré una comunicación constante con el cliente para garantizar que los objetivos del análisis se cumplan y los resultados sean claros y accionables.
La información será presentada en diferentes formatos, adaptados a las necesidades de los equipos técnicos y de negocio.

Entregables por tipo de proyecto
## 🧩 Caso 1: Telecomunicaciones – CallMeMaybe

Entregables para el cliente:

Dashboard interactivo (Tableau Public):
Visualización dinámica de métricas clave (llamadas entrantes/salientes, duración, llamadas perdidas, tiempo de espera, rendimiento por operador).
→ Permite a los supervisores identificar operadores ineficaces de forma inmediata.

Informe analítico (.pdf):
Documento con resumen ejecutivo, análisis estadístico, conclusiones y recomendaciones prácticas.

Notebook de análisis (.ipynb):
Código documentado y reproducible para auditoría técnica o seguimiento posterior.

## 🧪 Caso 2: E-commerce – Prueba A/B

Entregables para el cliente:

Informe de resultados (.pdf):
Presentación clara de la validez del experimento, diferencias entre grupos y conclusiones con soporte estadístico (prueba z de proporciones).

Visualizaciones comparativas (PowerPoint o Tableau):
Gráficos de conversión y embudo de ventas, diseñados para la presentación ejecutiva.

Notebook técnico (.ipynb):
Análisis detallado de datos, tratamiento de duplicados, control de fechas y pruebas estadísticas implementadas en Python.

## 📚 Caso 3: SQL – Base de datos editorial

Entregables para el cliente:

Notebook de consultas SQL (.ipynb):
Consultas ejecutadas y explicadas paso a paso, con resultados tabulares.

Resumen analítico (.pdf):
Recomendaciones basadas en los resultados: autores más rentables, editoriales destacadas y oportunidades de mercado.

Exportación de resultados (.csv):
Archivos con tablas filtradas y resultados principales, listos para integrar en otros sistemas o dashboards.

## Formatos y medios de entrega

📊 Dashboard: publicado en Tableau Public, con enlace compartido en dashboard.txt.

📘 Presentaciones: elaboradas en PowerPoint y exportadas a PDF para entrega formal.

💻 Código y análisis: desarrollado en Jupyter Notebook (.ipynb) con comentarios, estructura modular y resultados reproducibles.

📂 Archivos de respaldo: datasets procesados, tablas resumidas y gráficos exportados a formato .csv o .png según corresponda.

## Comunicación con el cliente

Reunión inicial: definición de objetivos, KPIs e indicadores de rendimiento esperados.

Revisión intermedia: presentación de avances y validación de enfoque analítico.

Entrega final: exposición ejecutiva de resultados, hallazgos y recomendaciones en PDF y dashboard.

Feedback post-entrega: reunión breve para resolver dudas o sugerencias sobre los análisis.

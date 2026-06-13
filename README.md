# Sprint9-Proyect-Landing_Experiment

Descripción

En este proyecto analicé un experimento A/B realizado sobre la página de inicio de un sitio de comercio electrónico. El objetivo fue evaluar si una nueva versión de la landing page generaba mejoras en la tasa de conversión y en el valor económico generado por los usuarios.
A través de análisis exploratorio, pruebas estadísticas e interpretación de resultados, se buscó proporcionar una recomendación basada en datos para apoyar la toma de decisiones del equipo de marketing.

Objetivo del Proyecto

Determinar si existen diferencias estadísticamente significativas entre las versiones A y B de la landing page respecto a:
Tasa de conversión.
Gasto promedio por usuario convertido.
Comportamiento según fuente de tráfico.
Comportamiento según tipo de usuario.
El objetivo final fue recomendar qué versión debería implementarse en producción.

Dataset

Fuente: Dataset académico proporcionado por TripleTen.
Cada registro representa un usuario expuesto a una única versión de la página.
Variables principales
Versión de landing page (A o B)
Región geográfica
Dispositivo utilizado
Fuente de tráfico
Tipo de usuario (Nuevo o Recurrente)
Conversión (0 = No convirtió, 1 = Convirtió)
Gasto generado por el usuario

Herramientas Utilizadas

Python
Pandas
NumPy
SciPy
Matplotlib
Seaborn
Jupyter Notebook

Metodología

1. Validación y exploración de datos
Revisión de tipos de datos
Verificación de valores faltantes
Validación del balance entre grupos A y B
Exploración inicial de métricas clave
2. Comparación de gasto promedio
Se analizaron únicamente los usuarios que realizaron una conversión para evitar sesgos derivados de registros con gasto igual a cero.
Se aplicaron pruebas estadísticas para evaluar si existían diferencias significativas entre ambas versiones.
3. Comparación de tasa de conversión
Se calcularon las tasas de conversión para cada grupo experimental y se evaluó si las diferencias observadas podían atribuirse al azar o representaban un efecto real.
4. Segmentación de usuarios
Se exploró el comportamiento de conversión según:
Fuente de tráfico
Tipo de usuario
Región
Dispositivo
5. Visualización de resultados
Se utilizaron gráficos para respaldar los hallazgos obtenidos mediante el análisis estadístico.

Técnicas Aplicadas

Análisis Exploratorio de Datos (EDA)
Estadística descriptiva
Pruebas de hipótesis
Comparación de medias
Prueba Z para proporciones
Tablas de contingencia
Segmentación de usuarios
Visualización de datos

Principales Preguntas de Negocio

¿Qué versión genera una mayor tasa de conversión?
¿Qué versión genera un mayor ingreso por usuario convertido?
¿La fuente de tráfico influye en la conversión?
¿Existen diferencias entre usuarios nuevos y recurrentes?
¿Qué recomendaciones pueden derivarse del experimento?

Hallazgos

El análisis permitió:
Evaluar el desempeño relativo de las versiones A y B.
Identificar segmentos con comportamientos diferenciados.
Determinar si las diferencias observadas eran estadísticamente significativas.
Traducir los resultados en recomendaciones prácticas para el negocio.

Recomendaciones

Implementar la versión con mejor desempeño estadísticamente validado.
Priorizar los canales de adquisición con mayor conversión.
Diseñar estrategias diferenciadas para usuarios nuevos y recurrentes.
Continuar realizando pruebas A/B para optimizar la experiencia del usuario.

Aprendizajes

Este proyecto me permitió fortalecer habilidades en:
Diseño e interpretación de experimentos A/B.
Aplicación de pruebas estadísticas en escenarios de negocio.
Validación de hipótesis mediante evidencia cuantitativa.
Comunicación de resultados para stakeholders no técnicos.
Conversión de resultados estadísticos en recomendaciones accionables.

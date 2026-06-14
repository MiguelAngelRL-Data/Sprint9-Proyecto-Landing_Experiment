# Experimento A/B para Optimización de Landing Page

## Descripción del Proyecto

Una empresa de ecommerce realizó un experimento A/B para evaluar el impacto de una nueva versión de su landing page sobre dos métricas clave del negocio:

* Tasa de conversión.
* Gasto promedio por usuario convertido.

El objetivo fue determinar si la nueva versión generaba mejores resultados y proporcionar una recomendación basada en evidencia estadística para apoyar la toma de decisiones del equipo de marketing.

---

## Objetivo de Negocio

Determinar qué versión de la landing page debe implementarse en producción considerando:

* Tasa de conversión.
* Gasto promedio por usuario convertido.
* Comportamiento por fuente de tráfico.
* Comportamiento por tipo de usuario.

---

## Dataset

**Fuente:** Dataset académico proporcionado por TripleTen.

Cada registro representa un usuario expuesto a una única versión de la landing page dentro de un experimento A/B.

### Variables principales

* `landing`: versión de la página (A o B).
* `traffic_source`: fuente de tráfico.
* `user_type`: tipo de usuario (Nuevo o Recurrente).
* `converted`: indicador de conversión.
* `gasto`: monto gastado por el usuario.

---

## Herramientas Utilizadas

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Metodología

### 1. Validación y exploración de datos

* Revisión de tipos de datos.
* Verificación de valores faltantes.
* Validación del balance entre grupos A y B.
* Exploración inicial de métricas clave.

### 2. Comparación de gasto promedio

Se analizaron únicamente los usuarios que realizaron una conversión para evitar sesgos provocados por registros con gasto igual a cero.

Se aplicó una prueba t para determinar si existían diferencias significativas entre ambas versiones.

### 3. Comparación de tasa de conversión

Se calcularon las tasas de conversión para cada grupo experimental y se utilizó una prueba Z para evaluar la significancia estadística de las diferencias observadas.

### 4. Segmentación de usuarios

Se analizó la conversión según:

* Fuente de tráfico.
* Tipo de usuario.
* Región.
* Dispositivo.

<img width="649" height="669" alt="Cantidad de conversiones por tipo de usuario" src="https://github.com/user-attachments/assets/0f09ed7a-79d8-4abb-a591-c1d49c8280d9" /><img width="772" height="796" alt="Proporscion de conversion por tipo de usuario" src="https://github.com/user-attachments/assets/029856fb-bdba-428d-9d6a-340e7d809104" />


### 5. Visualización de resultados
<img width="762" height="674" alt="Tabla cantidad de conversiones" src="https://github.com/user-attachments/assets/80d45930-dbce-45b6-b233-8f8fbeeda2aa" />


Se desarrollaron visualizaciones para respaldar los hallazgos estadísticos y facilitar la interpretación de resultados.

---

## Principales Hallazgos

### Conversión

* La versión B obtuvo 3,194 conversiones.
* La versión A obtuvo 2,512 conversiones.
* La prueba Z confirmó que la diferencia observada es estadísticamente significativa.

**Insight:** La versión B genera más conversiones y demuestra un mejor desempeño general para incentivar acciones de compra.

### Gasto Promedio

* Versión A: 61.09
* Versión B: 68.75

La prueba t mostró una diferencia estadísticamente significativa entre ambas versiones.

**Insight:** Los usuarios convertidos en la versión B generan un mayor valor económico para el negocio.

### Fuente de Tráfico

Se identificó una relación estadísticamente significativa entre la fuente de tráfico y la conversión.

Los canales Organic y Ads concentraron el mayor volumen de conversiones, mientras que Email mostró una proporción de conversión competitiva.

**Insight:** Existen oportunidades para optimizar la inversión en marketing digital enfocándose en los canales con mejor desempeño.

### Tipo de Usuario

No se encontraron diferencias estadísticamente significativas entre usuarios nuevos y recurrentes.

**Insight:** La landing page mantiene un comportamiento consistente independientemente de la experiencia previa del usuario.

---

## Recomendaciones de Negocio

* Implementar la versión B de la landing page.
* Priorizar la inversión en canales Organic, Ads y Email.
* Analizar oportunidades de mejora en canales con menor desempeño relativo.
* Mantener estrategias orientadas tanto a usuarios nuevos como recurrentes.

---

## Habilidades Demostradas

* Análisis Exploratorio de Datos (EDA).
* Estadística descriptiva.
* Pruebas de hipótesis.
* Prueba t para comparación de medias.
* Prueba Z para comparación de proporciones.
* Segmentación de usuarios.
* Visualización de datos.
* Storytelling con datos.
* Traducción de resultados estadísticos en recomendaciones de negocio.

---

## Conclusión

La versión B de la landing page mostró un desempeño superior tanto en tasa de conversión como en gasto promedio por usuario convertido.

Los resultados obtenidos proporcionan evidencia estadística suficiente para recomendar su implementación y respaldan decisiones orientadas a maximizar el valor generado por las iniciativas de marketing digital.

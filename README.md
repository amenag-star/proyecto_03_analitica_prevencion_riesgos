# Proyecto 03: Análisis de Accidentabilidad Laboral en Chile

## 1. Contexto del proyecto

Este proyecto forma parte de un portafolio de Data Science aplicado a prevención de riesgos laborales, seguridad ocupacional y análisis de datos públicos.

El análisis utiliza datos de accidentabilidad laboral en Chile, junto con información de trabajadores protegidos, con el objetivo de transformar registros públicos en indicadores útiles para la gestión preventiva y la toma de decisiones basada en evidencia.

El proyecto combina experiencia en prevención de riesgos con herramientas de análisis de datos, permitiendo identificar tendencias, sectores críticos, diferencias regionales, mecanismos frecuentes de accidente y oportunidades de mejora en la calidad del registro.

## 2. Objetivo del análisis

Analizar la accidentabilidad laboral en Chile mediante indicadores descriptivos y tasas de accidentabilidad, con el fin de identificar patrones relevantes para la gestión preventiva.

## 3. Preguntas de análisis

* ¿Cómo ha evolucionado la accidentabilidad laboral en Chile entre 2015 y 2024?
* ¿Qué diferencias existen entre accidentes del trabajo y accidentes de trayecto?
* ¿Qué regiones concentran más accidentes laborales?
* ¿Qué regiones presentan mayor tasa de accidentabilidad relativa?
* ¿Qué actividades económicas concentran mayor cantidad de accidentes?
* ¿Qué sectores presentan mayor accidentabilidad por cada 100 trabajadores protegidos?
* ¿Qué organismos administradores concentran más accidentes?
* ¿Cuáles son las formas de accidente más frecuentes?
* ¿Qué partes del cuerpo son más afectadas?
* ¿Qué agentes del accidente aparecen con mayor recurrencia?
* ¿Cómo varía la accidentabilidad según tamaño de empresa y sexo?

## 4. Fuente de datos

Los datos utilizados corresponden a bases públicas relacionadas con accidentabilidad laboral y trabajadores protegidos en Chile.

Las bases fueron procesadas, limpiadas y analizadas mediante Python, utilizando principalmente Pandas, Matplotlib y Jupyter Notebook.

## 5. Metodología

El proyecto se desarrolló en las siguientes etapas:

1. Carga de datos públicos.
2. Revisión inicial de estructura, columnas y tipos de datos.
3. Limpieza y estandarización de variables.
4. Preparación de variables temporales a partir del periodo.
5. Identificación de años completos para evitar distorsiones por periodos parciales.
6. Análisis exploratorio de accidentabilidad anual.
7. Comparación entre accidentes del trabajo y accidentes de trayecto.
8. Cálculo de tasas de accidentabilidad por cada 100 trabajadores protegidos.
9. Análisis por región, actividad económica, organismo administrador, tamaño de empresa y sexo.
10. Análisis técnico-preventivo según forma del accidente, agente y parte del cuerpo afectada.
11. Exportación de tablas resumen y gráficos principales.

## 6. Herramientas utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Git y GitHub

## 7. Principales hallazgos

El análisis muestra una disminución general de los accidentes laborales entre 2015 y 2019, seguida de una caída marcada en 2020. Esta disminución podría estar influenciada por el contexto de la pandemia por COVID-19, menor presencialidad, restricciones de movilidad y cambios en la operación normal de diversas actividades económicas.

Los accidentes del trabajo concentran la mayor proporción del total anual, mientras que los accidentes de trayecto mantienen una participación menor, pero relevante para la gestión preventiva.

Al calcular tasas de accidentabilidad por cada 100 trabajadores protegidos, se observa que el análisis relativo entrega una lectura más precisa que los conteos absolutos. Esto permite diferenciar entre zonas o sectores con alto volumen de accidentes y aquellos con mayor accidentabilidad proporcional.

A nivel regional, la Región Metropolitana concentra la mayor cantidad absoluta de accidentes, pero no necesariamente representa la mayor tasa relativa. Esto demuestra la importancia de comparar los accidentes con la cantidad de trabajadores protegidos.

Por actividad económica, sectores como comercio, construcción, manufactura, transporte y actividades administrativas concentran una parte importante de los accidentes. Sin embargo, al observar tasas, destacan actividades como manufactura, construcción, pesca, transporte y agricultura, lo que sugiere mayor exposición relativa a riesgos laborales.

Los análisis preventivos muestran que las caídas de personas, accidentes con vehículos, objetos corto-punzantes, golpes, sobreesfuerzos, herramientas, materiales, vehículos, máquinas y condiciones del entorno de trabajo son factores relevantes dentro de la accidentabilidad observada.

También se identificó una alta presencia de registros clasificados como “Sin Información” en algunas variables, lo que representa una oportunidad de mejora en la calidad del registro y clasificación de accidentes.

## 8. Resultados exportados

El proyecto genera archivos procesados en la carpeta:

```text
outputs/reportes/
```

Y gráficos principales en:

```text
outputs/graficos/
```

Entre los resultados exportados se incluyen:

* Accidentes anuales completos.
* Participación de accidentes según origen.
* Tasa anual de accidentabilidad.
* Indicadores por región.
* Indicadores por actividad económica.
* Indicadores por organismo administrador.
* Accidentes por forma del accidente.
* Accidentes por parte del cuerpo afectada.
* Accidentes por agente del accidente.
* Indicadores por tamaño de empresa.
* Tasa de accidentabilidad según sexo.

## 9. Conclusión

Este proyecto demuestra cómo el análisis de datos puede aportar valor a la prevención de riesgos laborales, permitiendo pasar desde registros operacionales a indicadores útiles para la toma de decisiones.

La combinación de conteos absolutos, tasas relativas y análisis técnico-preventivo permite identificar prioridades, diferenciar niveles de riesgo y orientar acciones de control, capacitación, fiscalización y mejora continua.

El proyecto refuerza la importancia de utilizar datos para apoyar una gestión preventiva más objetiva, trazable y basada en evidencia.

## 10. Próximos pasos

Como próximos pasos se propone:

* Crear un dashboard interactivo en Tableau o Power BI.
* Profundizar el análisis cruzando actividad económica, región y forma del accidente.
* Analizar tendencias mensuales o estacionales.
* Incorporar variables externas como empleo, movilidad o actividad económica.
* Mejorar la visualización ejecutiva de indicadores preventivos.
* Preparar una publicación profesional para LinkedIn.

# Impacto del estrés térmico ambiental en la incidencia cardiovascular aguda: Un análisis basado en telemetría satelital

**Autores:** Nayara López de Armentia, Aurora Real, Álex Sanz
**Asignatura:** Fuentes de Datos Biomédicos y Web Semántica  
**Grado:** Ingeniería de la Salud (Universidad de Burgos)

## Introducción
La biometeorología humana estudia la interacción entre las variables atmosféricas y la salud de las personas a escala meteorológica. En este proyecto uniremos datos ambientales (temperaturas extraídas de la telemetría satelital de la NASA) con datos clínicos para analizar el impacto del estrés térmico en las enfermedades cardiovasculares.

## Objetivos
El objetivo principal es comprobar si existe una relación directa entre los episodios de olas de frío y el aumento en la incidencia de infartos agudos de miocardio. Para ello, uniremos ambas bases de datos utilizando un flujo de trabajo de ciencia de datos y el paquete `dplyr` en RStudio, cruzando los indicadores ambientales con las tasas de altas hospitalarias.

## Estructura del repositorio
Este proyecto se organiza de la siguiente manera:
* `INPUT/DATA/`: Contiene las bases de datos originales (NASA y sanitarias).
* `OUTPUT/`: Almacena las gráficas, mapas y tablas de resultados generadas durante el análisis.
* `Seminario_NASA_Corazon.Rproj`: Archivo de entorno de RStudio que actúa como acceso directo al directorio de trabajo.
* `Seminario_NASA.Rmd`: Documento autocontenido con el código, la narrativa y los resultados del estudio.
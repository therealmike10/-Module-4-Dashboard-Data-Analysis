# Module 4: Dashboard and Data Analysis (Final Project)
Proyecto final del Módulo 4 del curso Data &amp; Analytics V3 de ThePower, desarrollado por Miguel Encinas. Este proyecto se centra en el análisis de las estadísticas de los **jugadores de la NBA durante los partidos disputados los 6 primeros meses de la temporada 24/25**. Este dashboard nos va a permitir estudiar los promedios de las diferentes estadísticas para todos los jugadores de liga desde Octubre de 2024 hasta Febrero de 2025; no sólo eso, también podremos ver el resumen de las estadísticas por equipo o incluso por conferencia. Para ello, se realizaron los siguientes pasos, correspondientes a las diferentes etapas del ciclo de vida de los datos.

## ⬇️ Descarga de los datos
Los datos fueron descargados del repositorio **Kaggle**, en concreto desde el enlace [Datos NBA 24/25](https://www.kaggle.com/datasets/eduardopalmieri/nba-player-stats-season-2425?resource=download), que se puede visitar para comprobar la descripción detallada de las diferentes columnas que aparecen en la tabla de datos.

## 🔧 Limpieza y transformación de los datos
Los datos fueron limpiados y transformados para mejorar su análisis. A priori, no fue elminada ninguna fila ni columna, ya que **los datos presentaban coherencia e integridad de manera general**. Se modificó el **nombre de algunas columnas, así como de su contenido**, para mejorar su legibilidad o entendimiento por parte de público no familiarizado con dichos datos. Se crearon a su vez **nuevas columnas para añadir más información útil** que pudiera ser empleada más tarde en la creación de tablas dinámicas y el dashboard. Por último, se realizó un **filtrado de cierta parte de los datos** que se consideraban poco relevantes para apartarlos del análisis.

## 📑 Creación de tablas dinámicas
Tras la transformación de los datos, se crearon diferentes tablas dinámicas, **recogiendo los KPI y los principales datos de interés**. Se trabajo principalmente con los promedios de las diferentes estadísticas, y se realizaron tablas dinámicas de ciertas estadísticas a lo largo de los meses, gracias a las modificaciones realizadas en la columna de la fecha. Por último, se añadieron diferentes **segmentaciones de datos** que funcioanarán como filtros en el dashboard.

## 📊 Creaciónd del dashboard
Tras el establecimiento de las tablas dinámicas, finalmente se crea un dashboard que recoge la información más relevante de los datos con los que hemos trabajado. Esta información se divide en dos zonas de KPIs en los bordes del dashboard, una zona de gráficas en el centro, y una zona de filtros en la franja inferior del dashboard. Además, el archivo Excel con macros aporta una personalización extra, ya que al seleccionar la conferencia, además de realizar el filtrado, el dashboard adquiere los colores de la conferencia correspondiente.

## ⏩ Funcionamiento del dashboard (recomendado)
En primer lugar, selecciona tu conferencia para realizar un primer cribado de equipos y jugadores. Tras esto, puedes seleccionar un mes concreto. Una vez realizados estos filtros, selecciona el equipo en el que estás interesado, y te aparecerán los promedios de las estadísticas de dicho equipo. A partir de ahí, puedes buscar a un jugador de dicho equipo en concreto, el equipo contra el que se ha enfretado o ambas opciones a la vez. Otra opción válida es filtrar por un equipo rival, para ver el promedio de estadísticas que dicho equipo recibe, lo cual también puede resultar interesante.

## ℹ️ Información de interés
**database_24_25 (original data).csv**: Archivo .csv original, descargado directamente desde Kaggle.
</br>
</br>
**Module_4_Project.xlsx**: Archivo que contiene los datos tratados así como el dashboard final, SIN macros.
</br>
</br>
**Module_4_Project_MACROS.xlsm**: Archivo que contiene los datos tratados así como el dashboard final, CON macros.
</br>
</br>
**Module_4_Project_Workflow.docx**: Informe detallado de los pasos seguidos para elaborar este proyecto.

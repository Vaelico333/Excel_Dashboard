# Tendencias globales de la música en streaming :guitar: :trumpet:

### :bar_chart: Análisis y comprensión de las preferencias de los oyentes

## :scroll: Descripción

En este trabajo, analizaremos varias estadísticas de diversos países, plataformas y rangos de edad, con el objetivo de entender mejor las tendencias y preferencias de los oyentes de música en streaming.  
  
Para la realización de este dashboard, descargué un archivo CSV de [Kaggle](https://www.kaggle.com/datasets/atharvasoundankar/global-music-streaming-trends-and-listener-insights), que por suerte estaba muy bien hecho y no requirió de reestructuración ni limpieza.  
  
Al analizar los datos, consideré que casi todos eran relevantes, excepto el de artista más escuchado, ya que había una discrepancia entre el artista más escuchado y el género musical, y deduje que es porque la lista de artistas es demasiado limitada. Por ello, decidí no incluirlo en mi análisis.  
  
Después creé las tablas dinámicas necesarias en la hoja de Análisis, y los gráficos asociados a ellas, y finalmente creé el dashboard en la tercera hoja con la siguiente estructura:
  
- En primer lugar, se muestran tres KPIs fundamentales para entender los datos: número de usuarios, subscripción más popular (de pago o gratis) y la media de minutos escuchados al día por persona.  
  
-A la izquierda se muestra la distribución por países de las plataformas de streaming más utilizadas y de los géneros musicales más escuchados.  
  
En el centro, primero exploramos el uso de las listas creadas por la plataforma de recomendación de canciones (discover weekly) y el porcentaje de canciones que los usuarios repiten, luego el uso de la lista de recomendación según edad, y por último, qué edad promedio escucha cada género musical.  
  
A la derecha, queda representada la distribución de usuarios de pago respecto a los gratuitos, y finalmente se muestra la distribución de minutos de escucha según la hora del día (mañana, tarde o noche).  
  
Finalmente, he incluido varios paneles de segmentación de datos para poder visualizar los efectos de cada dato en los demás, por ejemplo el país en el género musical, o la edad en la probabilidad de elegir una suscripción premium, gracias a las gráficas del dashboard.

## :spiral_notepad: Estructura

Todos los archivos están recogidos en una sola carpeta.

## :computer: Instalación y requisitos

El único requisito es disponer de Microsoft Excel. Utilizar otros programas impedirá ejecutar varias funciones imprescindibles para la correcta visualización del dashboard.

## :chart_with_upwards_trend: Resultados y conclusiones

El dashboard generado se puede utilizar tanto para estudiar tendencias culturales (como el género más escuchado en un país o una generación), como para extraer conclusiones de tipo empresarial: a qué segmento de la población es más fácil venderle una suscripción premium, por ejemplo.  

Con el estudio de las listas "discover weekly" y las repeticiones de canciones, podemos inferir qué tipo de personas son más curiosas o cuáles se aferran más a canciones que ya conocen.  
  
Por último, al poder filtrar según el segmento del día, es más sencillo decidir en qué momento lanzar según qué campañas publicitarias: por ejemplo, Spotify tiene una mayor proporción de gente con cuenta premium que escucha música por las noches, y la menor proporción es la que escucha música por las tardes. En ese segmento, la música más escuchada en promedio es la música clásica, seguida por el country y el reggae.

## :hand: Contribuciones

Al ser un proyecto tipo examen, no se aceptan contribuciones.

## :fountain_pen: Autores y agradecimientos

Autor: [Darío Zoreda](https://www.linkedin.com/in/dar%C3%ADo-zoreda-gallego/)

# FDS-2024-2-SC51
<h2>Objetivo del proyecto</h2>
<p>Desarrollar una propuesta de análisis y analítica a partir de un conjunto de datos, aplicando la
metodología CRISP-DM, y teniendo las siguientes consideraciones:</p>

<br>

- Crear conocimiento y valor a partir de los datos.

<br>

- Fundamentar y tomar decisiones basadas en los datos.

<br>

<p>Este proyecto de analítica tiene como finalidad conocer las tendencias de los videos de Youtube en ocho países, los cuales son: EE.UU., Canadá, Alemania, Francia, Gran Bretaña, México, India y Corea del sur. De esta forma, se decidió dividir el proyecto por cada país descrito y encargar cada fracción a un equipo de trabajo. En ese sentido, este informe, desarrollado por nuestro equipo de trabajo, está centrado en el análisis de tendencias de videos de Youtube en el país Francia (FR).</p>

<p>Cabe mencionar que, el cliente que solicitó el desarrollo de este proyecto es una importante empresa de marketing digital, la cual desea obtener respuestas a varios requerimientos de información, entre las cuales, destacan las respuestas relacionadas a las categorías de mayor tendencia y/o popularidad, al aumento o disminución del tiempo transcurrido por video a lo largo de los años, a los canales más y menos frecuentes en tendencia, y a los estados en los que existen más reacciones por parte de la audiencia. A fin de obtener las respuestas a estos requerimientos (extracción de conocimiento), se realiza el uso de la metodología Crisp-DM.</p>

<p>La metodología CRISP-DM permite una constante comunicación entre todos los integrantes
del equipo de trabajo durante el proceso de desarrollo de un proyecto de analítica, lo cual
permite la adaptación a los cambios de los requisitos, diseño y otros factores.</p>
<h2>Nombre los alumnos participantes</h2>

<p>Intregantes del equipo:</p>
- U202316342 - Edson Fabrizio Vásquez Trujillano
<br>
- U202220230 - Andre Angel Chipana Rios
<br>
- U202220177 - Enzo Daniel Medina Oropeza
<br>


<h2>Descripción del conjunto de datos</h2>

<p>El conjunto de datos ha utilizar en el análisis proviene de un dataset denominado como “Trending YouTube Video Statistics”, o, en español, “Tendencias de las estadísticas de videos de YouTube”, creado por el usuario “Mitchell J” y publicado en el sitio web “kaggle” en 2019. Esta base de datos de dominio público recopila los datos que comúnmente utiliza Youtube para actualizar los primeros puestos de la lista de vídeos en tendencia en su propia plataforma.</p>

<p>Teniendo en cuenta esta base de datos, se realizó una extracción de una sección de esta misma, correspondiente al país Francia, y se procedió a añadir columnas/variables de interés correspondientes al lugar de origen del video (“state”, “lat”, “lon”, “geometry”). De esta forma, se dió como resultado el conjunto de datos que se utilizará en el análisis propuesto por este trabajo.</p>

<h2>Conclusiones</h2>

<p>Comprender el objetivo del proyecto y los requerimientos del cliente permite establecer una dirección en el desarrollo del proyecto, sobre qué datos serán importantes en los modelos a desarrollar y, por ende, qué datos se deberán preprocesar.</p>
<p>El preprocesamiento de datos es necesario. Por un lado, algunas acciones permiten que los datos sean mucho más fáciles de procesar en los modelos, como es el caso de transformar un tipo de dato a otro o la creación de nuevas variables. Por otro lado, otras acciones permiten que la visualización final de los datos sea mucho más clara y perceptible visualmente, como el caso con los métodos de escalado, normalización y transformación.</p>
<p>Sobre los resultados obtenidos del proyecto, hemos podido generar las siguientes respuestas:</p>
- La categoría “Entertainment” (Entretenimiento) lidera como la categoría con más videos en tendencia en Francia.<br>
- La categoría que posee más “me gusta” es “Music” (música), mientras que la que posee menos es “Trailers” (trailers).<br>
- La categoría con mayor ratio de “likes” sobre “dislikes” es “Nonprofits & Activism” (Activismo).<br>
- La categoría con mayor ratio de “views” sobre “comment_count” es “Auto & Vehicle” (Autos y vehículos).<br>
- El volumen de videos en tendencia se mantiene relativamente estable a lo largo del tiempo, con pequeñas fluctuaciones en algunos períodos específicos.<br>
- “Nonprofits & Activism” es la categoría que recibe más comentarios positivos.<br>
- Se determina que es factible realizar predicciones de la base de datos.<br>

<h2>Colab Laboratory</h2>
https://colab.research.google.com/drive/1EFs3wiD8G9n33RUlUSpJSwl_2zZ_iaF-?usp=sharing

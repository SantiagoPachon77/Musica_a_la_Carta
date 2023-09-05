<p align="center">
  <img src="./img/Img1.PNG" alt="Size Limit CLI" width="738">
</p>
¿Cómo optimizamos la satisfacción y retención de usuarios mediante recomendaciones musicales personalizadas con base en el estado del ánimo del usuario?

La motivación detrás de este proyecto surge de la sobrecarga de opciones musicales en la era digital debido al acceso a un vasto catálogo de música, que a veces puede resultar abrumador para los usuarios. En muchas ocasiones, los usuarios se sienten perdidos entre la multitud de opciones, lo que conduce a una experiencia despersonalizada y, en última instancia, a la pérdida de interés. Además, reconocemos la importancia de la emoción y la conexión en la música, ya que sabemos que la música tiene el poder de influir en nuestras emociones y estados de ánimo. Nuestra meta es aprovechar esta capacidad para crear una experiencia musical que no solo sea placentera, sino que también establezca una conexión emocional profunda entre los usuarios y la música que escuchan.

Los clientes potenciales de este proyecto son los usuarios de servicios de streaming de música que desean compartir su estado de ánimo para recibir recomendaciones más personalizadas. El contexto organizacional donde surge este problema es el ámbito de las empresas que ofrecen este tipo de servicios. Estas plataformas buscan continuamente mejorar su servicio con el fin de satisfacer y retener a la mayor cantidad posible de usuarios.

Para resolver el problema, utilizaremos un algoritmo híbrido de recomendación que combinará filtros colaborativos y basados en contenido para generar una lista de recomendaciones. Por ejemplo, podríamos utilizar la recomendación colaborativa para seleccionar un conjunto inicial de elementos y luego refinar esa lista utilizando el filtrado basado en contenido. Con esto, optimizaremos la satisfacción de los usuarios y aumentaremos su retención.

<p align="center">
  <img src="./img/img2.png" alt="Size Limit CLI" width="738">
</p>

Características
========
1.	valence: Una medida de la positividad de una canción. Valores más altos indican canciones más alegres.
2.	year: El año de lanzamiento de la canción.
3.	acousticness: Una medida de cuán acústica es una canción. Valores cercanos a 1 indican alta acústica.
4.	artists: El nombre de los artistas que realizaron la canción.
5.	danceability: Una medida de cuán adecuada es una canción para bailar.
6.	duration_ms: La duración de la canción en milisegundos.
7.	energy: Una medida de la energía de la canción. Valores más altos indican canciones más enérgicas.
8.	explicit: Un indicador binario que indica si la canción contiene contenido explícito (1) o no (0).
9.	id: Un identificador único para la canción.
10.	instrumentalness: Una medida de cuánta presencia de voz o palabras tiene la canción. Valores más altos indican canciones instrumentales.
11.	key: La tonalidad de la canción.
12.	liveness: Una medida de cuán en vivo suena una grabación. Valores más altos indican que suena más en vivo.
13.	loudness: Una medida del volumen general de la canción.
14.	mode: La modalidad de la canción (mayor o menor).
15.	name: El nombre de la canción.
16.	popularity: La popularidad de la canción.
17.	release_date: La fecha de lanzamiento de la canción.
18.	speechiness: Una medida de cuán "hablada" es una canción en lugar de cantada.
19.	tempo: El tempo de la canción (ritmo o velocidad).

Requerimientos
============
* Linux or macOS or Windows
* Bash for Windows (`git bash` should suffice)
* version > python 3.5

Artículos
=====
* [Song Recommendation System based on Mood Detection using Spotify's Web API](https://doi.org/10.1109/iihc55949.2022.10060806)
* [Music Recommendation System Using Real Time Parameters](https://doi.org/10.1109/raeeucci57140.2023.10134257)
* [Music Recommendation System using Hybrid Approach](https://doi.org/10.1109/icears56392.2023.10085059)
* [Using PCA and K-Means to Predict Likeable Songs from Playlist Information](https://doi.org/10.1109/uksim.2018.00017)
* [Analysis of Clustering Algorithms for Music Recommendation](https://doi.org/10.1109/i2ct54291.2022.9824160)
* [Comparative Analysis of Different Approaches to the Music Recommendation System](https://doi.org/10.1109/iccci56745.2023.10128645)
* [Personalized Music Recommendation System using Hybrid Deep Birch Data Analytics Method](https://doi.org/10.1109/icmnwc56175.2022.10031988)

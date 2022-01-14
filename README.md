# Chess_dashboard: User-customized chess.com data based dashboard using R.

## Background
La inspiración de este proyecto viene de Spotify Wrapped, un evento realizado anualmente en el que la empresa Spotify, famosa aplicación de música en streaming, muestra a sus usuarios un resumen de su actividad a lo largo del año, cosa que es ampliamente compartida en redes sociales.

Decidimos entonces realizar un dashboard con esta idea, pero aplicada en el mundo del ajedrez, para lo que empleamos la plataforma de ajedrez online más usada a nivel global, siendo empleada tanto por celebridades de la élite del deporte como influencers ajenos al mismo.

Para hacer este resumen del 2021 del usuario, primero necesitamos aclarar que nos quedaremos con 3 categorías en las que se clasifican los juegos, según el tiempo disponible por cada jugador, bullet (hasta 1 minuto por jugador), blitz (entre 3 y 5 minutos por jugador) y rapid (entre 10 y 45 minutos por jugador), por lo que realmente tendremos un dashboard por cada una que únicamente se verán diferenciados por los datos mostrados.

## Pasos a seguir
Para poder generar un dashboard que incluye dichas informaciones, se debe ejecutar los códigos disponible en este GitHub (**Dashboard.Rmd**): se construirá un dashboard interactivo donde se muestra cómo fue la evolución del usuario a lo largo del año, distribución de las victorias, derrotas y empates y causas de las mismas.

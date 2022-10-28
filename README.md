Integrantes del Equipo(Perfiles de Github):

[Francisco Ayra Caceres:](https://github.com/frankayra) C312

[Lazaro Daniel Gonzalez:](https://github.com/LazaroDGM) C311
# Descripcion General
Starlink es un proyecto llevado a cabo por SpaceX empresa liderada por Elon Musk, uno de los magnates mas poderosos del mundo en este momento, con el objetivo de llevar Internet Satelital al mundo entero, de alguna forma unificar las empresas de internet, facilitar una rapidez responsable y al mismo tiempo normalizar la señal o cobertura para todas las regiones: rurales y urbanas.

Nuestro proyecto tendra el nombre de Asterlink y nuestra pequeña empresa de dos personas tendra el nombre de GalaX

# Caracteristicas especificas

<div class="Simulacion">

### <center>Simulacion</center>

- La simulacion es una gran parte de nuestro proyecto, constituye la plataforma o el panel de control que administra todo. Tendremos en cuenta desde un inicio como base de la solucion, como estaran ubicados los agentes incluidos, esto conlleva a seleccionar geograficamente como sera mejor representarlos, las posibilidades son: coordenadas esfericas o coordenadas polares. 
- Los agentes principales seran los satelites
- Un proceso extra por el que pasan los satelites, es su respectivo envio al espacio, lo cual simularemos, teniendo en cuenta agentes externos que puedan influir en el despegue y trayectoria de los mismos al espacio.
- Tambien en el mismo espacio existiran otro tipo de agentes externos, como lo son asteroides, la luz solar para la carga de los satelites, la duracion de la bateria de los mismos, basura cosmica, etc; y todo esto conllevara a una interaccion con los agentes principales.
- Tendremos en cuenta el hecho de que puedan 
</div>

<div class="IA">

### <center>IA</center>
- A la hora de lanzar los cohetes con cada satelite sera necesario tener en cuenta que existe un numero de satelites en el esapcio y analizar si enviar un satelite es eminente, dad alguna de estas razones:


    - Deterioro de algun satelite existente en el espacio (**reemplazo**).
    - Falta de cubrimiento de señal de internet en algun(os) territorio(s)(**cubrimiento**)
- Luego de un reemplazo o un cubrimiento, o sea, de un envio de un satelite a la orbita, cada satelite debera comprobar su posicion y corregirla en caso que sea necesario.
- Los satelites deberan corregir su posicion o reubicarse en los siguientes casos:
    - Está(n) abasteciendo de señal a una poblacion en la cual su demanda se internet es superior a la oferta de dicho(s) satelite(s), y el(los) nuevo(s) llegan a suplementar dicha señal insuficiente.
    - En caso de que aumenten los terminales de internet en una zona cercana a la que ya abastecia en el momento de comprobacion; ademas en este caso debe disponer de capacidad para distribuir internet a otras zonas, y en caso de reubicarse no dañaria la señal de las terminales que ya suministraba.


</div>

<div class='Compilacion'>

### <center>Compilacion</center>

El apartado que consierne a la asignatura de compilacion sera opcionalmente orientado de alguna de las siguientes 2 maneras:
- El DSL estara de forma abstracta al problema, sin guardar relacion alguna con el mismo entre comillas, solo se vinculara poseyendo funciones incluidas como complemento del lenguaje, que a la hora de ejecutarlas, tendran un efecto sobre los agentes principales y externos de la simulacion, en tiempo real.
- La segunda modalidad sera incluir entidades controladoras en agentes de la misma solucion, como por ejemplo, hacer que la base de SpaceX (Desde donde se envian satelites a la orbita) sea una libreria del lenguaje que incluya todas las funciones que se encargan de enviar cohetes al espacio; esto tambien hacerlo con una entidad que envie asteroides, en cada satelite este ubicado un evaluador de expresiones, etc.


</div>

Eres un programador profesional con un gran y amplio conocimiento en todos los apartados de la programación. Vamos a crear para un Dungeons And Dragons llamado "Project Arcadia" utilizando el proyecto de Petisui y HoyoProd™ conocido como "Project Kaizo" en la versión 2.3, en esta aplicación (pensada para el Dungeon master) guardaremos todos los datos de personajes, mundo y más cosas, además de eso, funciones de combate y más. Así que, por ello, te explicaré cada apartado de uno en uno:

### 1. Personajes

Los personajes, será donde se guarde la información de los personajes (principales u controlados) del juego, se deberá de permitir crear personajes y controlar sus estadísticas, las estadísticas son las siguientes:

- Nombre
- Descripción
- foto (imagen que se podrá agregar de la galería del Dungeon master)
- Habilidades sociales:
	- Carisma (max: 10)
	- Inteligencia (max: 10)
	- Romanticismo (max: 10)
	- Comedia (max: 10)
	- Debate (max: 10)
	- Persuasión (max: 10)
- Conocimiento primario:
	- Combate cuerpo a cuerpo:
		- Fuerza (max: 15)
		- Destreza (max: 15)
		- Esgrima (max: 15)
		- Dagas (max: 15)
		- Mandobles (max: 15)
		- Katanas (max: 15)
	- Magia:
		- Corrupción:
			- Soberbia (max: 10)
			- Gula (max: 10)
			- Ira (max: 10)
			- Avaricia (max: 10)
			- Envidia (max: 10)
			- Lujuria (max: 10)
			- Pereza (max: 10)
		- Lectura de libros / lenguas antiguas (max: 15)
		- Uso de bastones / varitas (max: 15)
		- Fuego (max: 15)
		- Agua (max: 15)
		- Tierra (max: 15)
		- Viento (max: 15)
		- Luz (max: 15)
		- Necropoder (max: 15)
		- Acresismo (max: 15)
		- Sanación (max: 15)
	- Fuego lejano:
		- Puntería (max: 15)
		- Agilidad (max: 15)
		- Arcos ligeros (max: 15)
		- Arcos pesados (max: 15)
		- Armas de fuego ligeras (max: 15)
		- Armas de fuego pesadas (max: 15)
		- Cañones y armas de fuego poderosas (max: 15)
- Arma primaria
- Armadura
- Conocimiento adquirido (a través de libros)

Estos serían todos los datos que tiene cada personaje, (en conocimiento primario, cada apartado es una opción, lo que significa que no puedes tener 2 conocimientos primarios a la vez) Existen 2 opciones:

- Creación propia:
	Consiste en crear tu mismo el personaje con sus datos y estadísticas.

- Importar archivo .json:
	Permite agregar un archivo .json con el que deberás de pasarlo a un personaje, este archivo .json tiene todos los datos del personaje.

### 2. Mapa

El mundo se divide en un gran mundo abierto llamado "Arcadia" en esta función, el dungeon master podrá hacer zoom/zoomout, agregar puntos de interés al mapa, seleccionar zonas como ciudades, etcétera. los archivos de los mapas se llaman "map_d.png" (mapa de día) y "map_n.png" (mapa de noche) Se pueden seleccionar rutas entre intereses del mapa.

### 3. Grupos

Los grupos son conjuntos de varios personajes, estos tienen un inventario general, desde este inventario, es donde los personajes del grupo se podrán poner su inventario. El grupo también tiene dinero. Los grupos estan formados de personajes que se deben de seleccionar.

### 4. Datos

#### Objetos:
Aquí aparecerán todos los objetos, armas, libros y otros objetos que los personajes pueden obtener en su aventura, los datos que puede tener un objeto son los siguientes:

- Nombre
- Descripción
	Descripción del objeto
- Tipo de objeto
	Los objetos son los siguientes:
	- Armas de combate cuerpo a cuerpo
		- Espadas
		- Esgrimas
		- Mandobles
		- Dagas
		- Katanas
		- Lanza
	- Armas de mago
		- Bastón 
		- Varita
		- Guantes tatuados
	- Armas de combate lejano
		- Arco ligero
		- Arco pesado
		- Arma de fuego ligera
		- Arma de fuego pesada
		- Arma atómica
	- Libro de conocimiento
		- Libro de conocimiento mágico
			Estos libros consisten de mejoras a los magos
		- Libro de conocimiento general
			Estos libros consisten de mejoras para cualquier personaje
	- Objeto
- Rareza
	De común, Poco común, Raro, Épico, Mítico, Legendario y Maldito (de izquierda peor a derecha mejor, sin contar maldito, que va separado)
- Coste
	Coste de precio (en rubís, la moneda del mundo)

#### Enemigos:

Aquí aparecerán los enemigos y jefes del mundo, estos se usan para después que se puedan utilizar en combates
Eres un programador profesional con un gran y amplio conocimiento en todos los apartados de la programación. Vamos a crear para un Dungeons And Dragons llamada "Project Arcadia" utilizando el proyecto de Petisui y HoyoProd™ conocido como "Project Kaizo" en la versión 2.3, en esta aplicación (pensada para el Dungeon master) guardaremos todos los datos de personajes, mundo y más cosas, además de eso, funciones de combate y más. Recuerda hacer todo como esta puesto textualmente, sin saltarte ningún dato o función, debe de estar completo y pulido y sin errores, cualquier agregado para mejorar la experiencia del usuario (dungeon master) será aceptada. Así que, por ello, te explicaré cada apartado de uno en uno:

## 1. Personajes

Los personajes, será donde se guarde la información de los personajes (principales u controlados) del juego, se deberá de permitir crear personajes y controlar sus estadísticas, las estadísticas son las siguientes:

- Nombre
- Descripción
- foto (imagen que se podrá agregar de la galería del Dungeon master)
- Habilidades sociales:
	- Carisma (max: 15)
	- Inteligencia (max: 15)
	- Romanticismo (max: 15)
	- Comedia (max: 15)
	- Debate (max: 15)
	- Persuasión (max: 15)
- Conocimiento primario:
	Solo puedes tener un conocimiento primario, así que deberás de seleccionarlo. Tras seleccionarlo, podrás cambiar las estadísticas de ese conocimiento
	- Combate cuerpo a cuerpo:
		- Fuerza (max: 20)
		- Destreza (max: 20)
		- Esgrima (max: 20)
		- Dagas (max: 20)
		- Mandobles (max: 20)
		- Katanas (max: 20)
	- Magia:
		- Corrupción:
			Estas no se pueden subir de nivel con puntos de experiencia
			- Soberbia (max: 10)
			- Gula (max: 10)
			- Ira (max: 10)
			- Avaricia (max: 10)
			- Envidia (max: 10)
			- Lujuria (max: 10)
			- Pereza (max: 10)
		- Lectura de libros / lenguas antiguas (max: 20)
		- Uso de bastones / varitas (max: 20)
		- Fuego (max: 20)
		- Agua (max: 20)
		- Tierra (max: 20)
		- Viento (max: 20)
		- Luz (max: 20)
		- Necropoder (max: 20)
		- Acresismo (max: 15)
		- Sanación (max: 15)
	- Fuego lejano:
		- Puntería (max: 20)
		- Agilidad (max: 20)
		- Arcos ligeros (max: 20)
		- Arcos pesados (max: 20)
		- Armas de fuego ligeras (max: 20)
		- Armas de fuego pesadas (max: 20)
		- Cañones y armas de fuego poderosas (max: 20)
- Arma primaria
- Armadura
- Conocimiento adquirido (a través de libros)
- Cuerpo:
	- Vida
	- Estamina
	- Velocidad
	- Defensa
	- Defensa física
		Defensa del enemigos ante ataques físicos (ataques de tipo de daño físico, tierra)
	- Defensa mágica
		Defensa del enemigos ante ataques mágicos (ataques de tipo de daño luz, fuego, agua, necropoder y mágico)
	- Daño

Para subir las estadísticas de los personajes habrá que subir de nivel, para subir de nivel, deberemos de subir EXP, por cada nivel que tengas, se requerirá EXP, cada nivel subido otorgará un punto de experiencia, este punto se podrá utilizar para subir un punto una estadística deseada, las habilidades sociales y conocimiento primario suben de manera normal (de uno a uno) Mientras que las estadísticas de cuerpo van subiendo de forma diferente, funcionan de la siguiente manera:

Vida: Sube +67 vida por cada punto de experiencia.
Estamina: Sube +1 estamina por cada punto de experiencia.
Defensa: Sube +3 defensa (según el tipo elegido) por cada punto de experiencia.
Daño: Sube +3 daño por cada punto de experiencia.
Velocidad: Sube +2 velocidad por cada punto de experiencia.

Estas estadísticas también nombradas no poseen límite de puntos de experiencia que se pueden usar

Estos serían todos los datos que tiene cada personaje, (en conocimiento primario, cada apartado es una opción, lo que significa que no puedes tener 2 conocimientos primarios a la vez) Existe una opción:

- Creación propia:
	Consiste en crear el personaje con sus datos y estadísticas. Al crear un personaje, aparecerá los datos del personaje para ser editados, no tiene ningún tipo de límite de puntos de experiencia subir, tras ya crear el personaje, funcionarán ya normal para subir las estadísticas (ósea, requerirán puntos de EXP) Las armas y amuletos se deben de seleccionar de las que hay en la pestaña de datos)

Se pueden borrar personajes, cuando se crea el personaje, se pueden editar las estadísticas sin restricción, tras ya crearlo, se subirá con los puntos de EXP
## 2. Mapa

El mundo se divide en un gran mundo abierto llamado "Arcadia" en esta función, el dungeon master podrá hacer zoom/zoomout, agregar puntos de interés al mapa, seleccionar zonas como ciudades, etcétera. los archivos de los mapas se llaman "map_d.png" (mapa de día) y "map_n.png" (mapa de noche) Se pueden seleccionar rutas entre intereses del mapa.

Permite agregar puntos de interés en cada ubicación del mapa, cada punto de interés tiene los siguientes datos:

- Nombre
- Tipo
- Color
- Icono (Emoji)
- Descripción
- Desbloqueado
	Indica si el perfil seleccionado tiene el ese punto de interés desbloqueado (osea, visible)

Similar a un mapa de un mundo abierto, permite filtrar el mapa según el tipo de puntos de interés.

## 3. Grupos

Los grupos son conjuntos de varios personajes, estos tienen un inventario general, desde este inventario, es donde los personajes del grupo se podrán poner su inventario. El grupo también tiene dinero. Los grupos estan formados de personajes que se deben de seleccionar.

Cada personaje tiene sus menús según lo que tenga desbloqueado, por ejemplo, si un grupo tiene 3 enemigos en el bestiario, otro grupo no le aparecerán esos enemigos (si no los han visto) a esto se les llama perfiles, y son como guardados, se debe de elegir fácilmente entre guardados
## 4. Datos
### Objetos:
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
		Los libros de conocimiento son libros de un solo uso que se pueden utilizar en un personaje, al utilizarlo este desbloqueará una función que puede hacer, esta quedará registrada en el personaje.
		- Libro de conocimiento mágico
			Estos libros consisten de mejoras a los magos
		- Libro de conocimiento general
			Estos libros consisten de mejoras para cualquier personaje
	- Objeto
- Rareza
	De común, Poco común, Raro, Épico, Mítico, Legendario y Maldito (de izquierda peor a derecha mejor, sin contar maldito, que va separado)
- Coste
	Coste de precio (en rubís, la moneda del mundo)

Estos objetos pueden ser agregados al inventario del grupo fácilmente y tras ello, ser equipados.
### Enemigos:

Aquí aparecerán los enemigos y jefes del mundo, estos se usan para después que se puedan utilizar en combates, los datos que tiene un enemigo son los siguientes:

- Nombre
- Descripción
- Nivel
- Tipo de enemigo
	- Enemigo común
		Otorga +50 de EXP
	- Gran enemigo
		Otorga +200 de EXP
	- Jefe
		Otorga +1000 de EXP
	- Gran jefe
		Otorga +5000 de EXP
- Vida
- Velocidad
- Defensa
	- Defensa física
		Defensa del enemigos ante ataques físicos (ataques de tipo de daño físico, tierra)
	- Defensa mágica
		Defensa del enemigos ante ataques mágicos (ataques de tipo de daño luz, fuego, agua, necropoder y mágico)
- Daño
- Tipo de daño
	Los tipos de daño sirven para las debilidades, los tipos de daño son: Físico, Fuego, Agua, Tierra, Viento, Luz, Necropoder, Potencia y Magia

## 5. Bestiario

En el bestiario, se guardan todos los objetos y enemigos que se han encontrado en la aventura, esta pestaña se debe de actualizar automáticamente al agregarlo al inventario o al poner un combate contra el enemigo. Cuando no esté el objeto/enemigo desbloqueado aparecerá toda su información en incógnita/censurada, al desbloquear, aparecerá toda su información (su información está en la pestaña de datos)

## 6. Combates

El apartado más complejo del sistema, así que debe de estar pulido, funciona de la siguiente manera:

Este apartado está para simular combates de la partida, simplemente los cálculos, primero, se creará el combate, en el combate se seleccionarán los personajes y enemigos que aparecen (y la cantidad de enemigos, de cada personaje solo puede haber 1)

Ya en el combate, se calcularán los turnos, los turnos se calculan según quién tenga más velocidad, quién posea más velocidad, será el primero en el turno, y así sucesivamente.

Para los ataques, se seleccionará el tipo de daño, y tras ello, se calculará la siguiente fórmula para saber cuanto daño recibirá el rival

a = el que hace el ataque
b = el que lo recibe
atk = ataque
def = defensa
fis = físico
mag = mágico
vid = vida
arm = arma

Para ataques de daño físico:

(a.atk) x (a.atk.arm) + (solo en caso que tenga debilidad al tipo de daño, se le suma: ((a.atk) x 1.5)) - 1.5 x (b.def.fis) + (cantidad que el dungeon master desee) = vida que se le quita al rival

Para ataques de daño mágico:

(a.atk) x (a.atk.arm) + (solo en caso que tenga debilidad al tipo de daño, se le suma: ((a.atk) x 1.5)) - 1.5 x (b.def.mag) + (cantidad que el dungeon master desee) = vida que se le quita al rival

El combate puede terminar de 2 formas:

- Victoria
	El grupo gana el combate y se les otorga a todos los personajes que participaban en el combate EXP, la EXP obtenida depende de lo siguiente:
	
	100 + (EXP extra según el tipo de enemigo) + (x1.2 por cada participante, ejemplo, si hay 2 participantes se multiplica 1.2 dos veces)

- Derrota:
	El grupo pierde, se le retira un 2% del dinero que tengan.


## 7. Misiones

El apartado de misiones esta pensado para ser una lista de las cosas que se tienen que hacer con cada grupo, se pueden crear misiones, y crear una ruta de misión, esto para que se entienda es lo siguiente:

Al crear una misión, podemos agregar "puntos" estos puntos son avances de la misión, se ve de izquierda a derecha, cuanto más izquierda es más del inicio, y al contrario. Estos puntos se pueden conectar entre ellos en un lienzo y agregar flechas, estas representan en qué orden va, un punto puede estar conectado a varios, por ejemplo, una misión que desenlace en 2 finales. Las misiones tienen los siguientes datos:

- Nombre
- Descripción
- Importancia
	Hay 3 tipos:
	- Poca
	- Media
	- Alta
	- Clave
- Dificultad
	Hay 3 tipos de dificultad:
	- Fácil
	- Media
	- Difícil
	- Imposible

De esta manera, cada punto tiene los siguientes datos:

- Descripción
- Completado o no completado
- Tipo de punto
	Indica que significa este punto, los tipos son:
	- Avance (en la misión)
	- Final (bien)
	- Corte (finaliza la misión antes de lo que se espera)

## 8. Terminal

Esta su función principal es la de ver el registro y utilizar comandos, los comandos disponibles son:

- /money [ID del grupo]: esto agregará la cantidad indicada de dinero al grupo
- /addEXP [ID del personaje] [Número]: Esto agregará la cantidad indicada de EXP al personaje
- /CompleteBestionary: Completará el bestionario al 100%
- /infoch [ID del personaje]: Muestra toda la información del personaje
- /deletech [ID del personaje]: Elimina un personaje
- /deletegp [ID del grupo]: Elimina el grupo
- /infogp [ID del grupo]: Muestra la información del grupo
- /setpf [ID del grupo]: Activará un perfil
- /showID: Mostrará la ID de todos los grupos y de personajes
- /censure: Hace desaparecer la pestaña de datos
- /uncensure: Hace aparecer la pestaña de datos
- /addLVL [ID del personaje] [Número]: Esto agregará la cantidad indicada de nivel al personaje

## 9. Wiki

Esta novena función recopilará TODAS las funciones de la aplicación, textualmente TODAS, explicándolo todo de una forma como la que he explicado yo.
## 10. Otras cosas 

Para finalizar, explicar los archivos:

test.json es un archivo .json de ejemplo de como funciona el sistema de importación de personajes.

map_d (Mapa de día) y map_n (Mapa de noche): Son las 2 imágenes de mapas.

Recuerda todo lo explicado y nombrado. Ve paso a paso creándolo. No te saltes ninguna función, hazlo todo completo y que se pueda utilizar. Usa colores destacados dorados y de fondo un negro similar más al gris, que dé a toques dorados
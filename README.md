# laberinto-Pharo
Implementación del Laberinto en Smalltalk Pharo 5
El Laberinto es el ejemplo que se utiliza en la asignatura Diseño de Software para ilustrar los patrones de diseño de Gamma et al.

version 14: Incluye elementos del Composite (Contenedor y Hoja), que son también de tipo ElementoMapa. Los elementos de tipo contenedor tienen "hijos" y operaciones para gestionar los hijos (agregarElemento y quitarElemento). Los contenedores también tienen una colección de ocupantes que sirve para saber si hay bichos o personajes en la habitación

version 15: se modifica la operación entrar:alguien

version 17: se define un hilo para cada bicho. Se adjunta el código del Playground.

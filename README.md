# laberinto-Pharo
Implementación del Laberinto en Smalltalk Pharo 5
El Laberinto es el ejemplo que se utiliza en la asignatura Diseño de Software para ilustrar los patrones de diseño de Gamma et al.

Versión 13 de la SolucionLaberinto importada de VisualWorks para Pharo. Esta versión incluye:
- Los patrones de las versiones anteriores: Composite, Decorator y Strategy
- El patrón Builder. Tiene un objeto Director que parsea un archivo JSON (se incluye un archivo de ejemplo)
- Bridge: las habitaciones "tienen" forma
- Personaje y Bichos (agresivo, golismero y vigilante)
- Los bichos funcionan como hilos independientes
- Los bichos y el personaje se pueden atacar (personaje ataca)

Como en Pharo no existe la colección List, hay que incluirla como subclase de OrderedCollection.

También es necesario instalar la librería NeoJSON (https://ci.inria.fr/pharo-contribution/job/EnterprisePharoBook/lastSuccessfulBuild/artifact/book-result/NeoJSON/NeoJSON.html)



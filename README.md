# Algoritmo Genético para TSP

Este es un script en JavaScript que implementa un algoritmo genético para resolver el problema del viajante de comercio (TSP, por sus siglas en inglés). El TSP consiste en encontrar el recorrido óptimo que visite todas las ciudades en un mapa, minimizando la distancia total recorrida.

## Funcionamiento

El algoritmo genético utiliza una población de individuos que representan posibles soluciones al problema. En cada generación, se seleccionan los mejores individuos para la reproducción, se aplican operadores genéticos como el cruce y la mutación, y se crea una nueva generación de individuos. El proceso se repite hasta que se alcanza un criterio de terminación.

## Parámetros

El script utiliza varios parámetros que pueden ajustarse para obtener mejores resultados:

- `POPULATION_SIZE`: Tamaño de la población.
- `ELITE_RATE`: Tasa de individuos élite que se mantienen sin cambios en cada generación.
- `CROSSOVER_PROBABILITY`: Probabilidad de realizar el cruce entre dos individuos.
- `MUTATION_PROBABILITY`: Probabilidad de aplicar la mutación a un individuo.
- `OX_CROSSOVER_RATE`: Tasa de cruce en el operador de cruce de orden (OX).
- `UNCHANGED_GENS`: Número de generaciones sin mejora para detener el algoritmo.

## Uso

El script puede ejecutarse en un entorno que admita JavaScript. Se recomienda utilizar un navegador web y abrir la consola de desarrollador para ver los resultados. A continuación, se muestran algunas funciones y su descripción:

- `init()`: Inicializa el lienzo y configura el evento de clic del ratón.
- `initData()`: Inicializa los datos y parámetros del algoritmo.
- `addRandomPoints(number)`: Agrega puntos aleatorios al mapa.
- `draw()`: Dibuja los puntos y la mejor ruta actual en el lienzo.
- `GAInitialize()`: Inicializa la población y calcula las distancias entre ciudades.
- `GANextGeneration()`: Genera la siguiente generación de individuos mediante selección, cruce y mutación.
- `countDistances()`: Calcula las distancias entre todas las ciudades.

¡Diviértete explorando el código y ajustando los parámetros para obtener mejores resultados en la resolución del TSP!


# Metro CDMX: DFS, BFS y Hill Climbing
Modelado del Metro de la CDMX como un grafo (estación = estado, moverse a una estación vecina = acción, costo unitario = 1) usando el esquema visto en clase: `Problem`, `GraphProblem`, `Node`.

Rutas:
1. Cuatro Caminos -> Pantitlán
2. Politécnico -> Tasqueña
3. Zapata -> Oceanía

## Abrir en Google Colab > Entorno de ejecución > Ejecutar todo
- `Metro_DFS_BFS.ipynb`: búsqueda en profundidad y en anchura.
- `Metro_HillClimbing.ipynb`: Hill Climbing con heurística = distancia en línea recta (km) a la estación meta, usando coordenadas aproximadas de las estaciones.

## Resultados (costo = número de kilomotros)
| Ruta | DFS | BFS | Hill Climbing |
|---|---|---|---|
| Cuatro Caminos -> Pantitlán | 18 | 18 | 22 |
| Politécnico -> Tasqueña | 46 | 20 | 20 |
| Zapata -> Oceanía | 53 | 13 | atascado en Canal del Norte |

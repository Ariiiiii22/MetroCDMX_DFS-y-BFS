# MetroCDMX_DFS-y-BFS

Modelado del Metro de la CDMX como un grafo (estación = estado, moverse a una estación vecina = acción, costo unitario = 1) usando lo visto en clase:
`Problem`, `GraphProblem`, `Node`, `depth_first_graph_search` y `breadth_first_graph_search`.

Rutas requeridas:
1. Cuatro Caminos -> Pantitlán
2. Politécnico -> Tasqueña
3. Zapata -> Oceanía

## Cómo ejecutarlo
Abre `Metro_DFS_BFS.ipynb` en Google Colab y ejecuta todas las celdas (`Entorno de ejecución > Ejecutar todo`).

## Resultados (costo = número de kilometros)
| Ruta | DFS | BFS |
|---|---|---|
| Cuatro Caminos -> Pantitlán | 18 | 18 |
| Politécnico -> Tasqueña | 46 | 20 |
| Zapata -> Oceanía | 53 | 13 |


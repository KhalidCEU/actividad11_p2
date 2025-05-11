## Grafos

> Defina los términos: grafo, grafo dirigido (o digrafo), cuándo un vértice es adyacente a otro, peso (o coste) de un grafo, camino, longitud de un camino, bucle en un grafo, ciclo, camino simple, grafo acíclico (o DAG), grafo conexo, grafo fuertemente conexo, grafo débilmente conexo y grafo completo.

- **Grafo**: Un **grafo** es una **estructura de datos** compuesta por un conjunto de **vértices** (o nodos) y un conjunto de **aristas** (o enlaces) que **conectan pares de vértices**. Puede ser representado como `G = (V, E)`

    Un grafo **no es lineal** porque sus elementos NO estan organizados de manera SECUENCIAL, cada elemento puede estar conectado a **0, 1 o VARIOS** otros elementos, lo que permite **multiples relaciones / caminos posibles** entre ellos

<div align="center">
    <img width="25%" src="assets/grafo.png"/>
</div>


- **Grafo dirigido**: Grafo en el que **las aristas tienen una dirección**, es decir, **cada arista** va de un **vértice origen** a un **vértice destino**.

- **Vertice adyacente a otro** = si **existe una arista** que los **conecta directamente**.

- **Peso (/coste) de un grafo**: **Valor numérico** asignado a **cada arista** que representa el costo, distancia asociada a **recorrer esa arista**.

- **Camino**: **Secuencia de vértices** en la que cada par consecutivo está conectado por una arista.

<div align="center">
    <img width="25%" src="assets/camino.png"/>
</div>

- **Longitud de un camino**: Número de aristas que **forman el camino**.

- **Bucle en un grafo** : **Arista** que conecta un vértice **consigo mismo**.

<div align="center">
    <img width="25%" src="assets/bucle.png"/>
</div>

- **Ciclo**: **Camino cerrado** en el que el **primer y último** vértice **coinciden** y no se repite ninguna arista ni vértice, salvo el primero y el último.

<div align="center">
    <img width="25%" src="assets/ciclo.png"/>
</div>

- **Camino simple**: Camino en el que **no se repite** ningún **vértice** (excepto posiblemente el primero y el último, si es un ciclo.)

- Grafo **acíclico** (o DAG): Grafo **dirigido** que **no contiene ciclos**.

<div align="center">
    <img width="25%" src="assets/DAG.png"/>
</div>

- Grafo **conexo**: Grafo **no dirigido** en el que existe **al menos 1 camino** entre cualquier **par de vértices**.

- Grafo **fuertemente conexo**: Grafo conexo en el que existe un **camino dirigido** entre cualquier par de vértices en **ambos sentidos**.

<div align="center">
    <img width="35%" src="assets/fuertemente_conexo.png"/>
</div>

- Grafo **débilmente conexo**: Grafo dirigido que, **al ignorar la dirección de las aristas**, es conexo.

<div align="center">
    <img width="30%" src="assets/debilmente_conexo.png"/>
</div>


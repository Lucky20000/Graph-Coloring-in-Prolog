# Graph Coloring in Prolog

## Aufgabe
Ein ungerichter Graph soll gefärbt werden. Die Knoten des Graphen sollen dabei so gefärbt werden, dass keine benachbarten Knoten die gleiche Farbe erhalten. Die verwendbaren Farben sollen als Parameter vorgegeben werden.

## Erklärung der Prädikate
Die Färbung des Graphen wird mit dem Prädikat `graph_Coloring/4` durchgeführt. Die Knoten werden als Liste übergeben. Jedes Element repräsentiert dabei einen Knoten. Die Kanten werden ebenfalls als Liste übergeben. Jedes Element repräsentiert dabei eine Kante zwischen zwei Knoten. Da der Graph ungerichtet ist, werden Kanten nur einmal definiert. Das heißt, um beispielsweise zu definieren, dass es im Graphen eine Kante zwischen den Knoten a und b gibt, reicht das Element (a,b) aus. Das Element (b,a) ist nicht mehr nötig. Die Farben, die verwendet werden sollen, werden als Liste übergeben. Jedes Element repräsentiert eine Farbe.

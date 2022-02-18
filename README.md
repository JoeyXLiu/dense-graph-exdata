# dense-graph-exdata

The exdata graphs generated by [MUSKETEER](https://github.com/sashagutfraind/musketeer)

The graph format is the same as the unweighted graph fromat used by [Metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview) and [KaHIP](https://kahip.github.io/):

For a graph G = (V, E), with `n` vertices and `m` edges, the header line contains the information of the graph `n m`. The remaining n lines store information about the structure of the graph. In particular, line `i` (excluding header and all comment lines) contains the index of all its neighbor vertices. The graph vertices are indexed from `1` to `n`.

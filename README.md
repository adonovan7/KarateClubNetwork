# KarateClubNetwork
An introduction into plotting and analyzing network data using the Karate Club dataset

## Data Source:
Zachary's Karate Club dataset

* From the CRAN documentation site:
> Social network between members of a university karate club, led by president John A. and karate instructor Mr. Hi (pseudonyms). The edge weights are the number of common activities the club members took part of. Zachary studied conflict and fission in this network, as the karate club was split into two separate clubs, after long disputes between two factions of the club, one led by John A., the other by Mr. Hi. The ‘Faction’ vertex attribute gives the faction memberships of the actors. After the split of the club, club members chose their new clubs based on their factions, except actor no. 9, who was in John A.’s faction but chose Mr. Hi’s club.

## Network Terminology:

1. **Assortativity** - the extent to which nodes clump together with other similar nodes and repel from non-similar nodes.
2. **Cliques** - complete 'neighborhoods' or subgraphs
3. **Scale-free** - degree distribution follows the power law
4. **Isomorphic** - an alternative representation of a graph that preserves the adjacency matrix of the data. In other words, it is a bijection or one-to-one function of the vertices of two graphs. 
  * **Automorphisms** constitute the set of all possible isomorphisms
5. **Adhesion** - edge connectivity; how many edges neeed to be removed to eliminate contact between two nodes
6. **Preferential Attachment** - The theory that well-connected nodes are more likely to acquire new connections than poorly connected nodes
7. **Centrality** - whether or not there is one or more "central" nodes around which the other nodes cluster. 
8. **Articulation Points** - outliers or poorly connected nodes
9. **Small World Model** - Most or all nodes are not neighbors but are still closely connected (have a small geodesic distance). Typically these follow a relatively symmetric shape
10. **Neighbors** - adjacent vertices/ nodes that are directly connected by an edge
11. **Geodesic Distance** - the shortest possible path from one node to another. Serves as a key indicator of network connectivity
12. **Diameter** longest path/ geodesic distance between nodes




#### Links to Data Sources:

1. https://cran.r-project.org/web/packages/igraphdata/igraphdata.pdf

2. https://github.com/igraph/igraphdata


#### More Resources:

1. http://kateto.net/networks-r-igraph

2. https://www.datacamp.com/courses/network-analysis-in-r

3. http://barabasi.com/networksciencebook/

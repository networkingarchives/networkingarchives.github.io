Online Appendix - Glossary


## Glossary

The following draws from a collaborative glossary compiled at [Early Modern Digital Agendas: Network Analysis](https://folgerpedia.folger.edu/EMDA_2017), an NEH-funded summer institute at the Folger Shakespeare Library in July 2017 (directed by Ruth Ahnert and Jonathan Hope, and at which the other authors were all distinguished visiting fellows).[^1]  


##### **actor**


    See _node._


##### **adjacency matrix**


    See _matrix_.


##### **arc**


    See _edge._


##### **betweenness centrality**


    A measurement of the infrastructural significance of a given _node_ or _edge_ in the network. It counts the number of _shortest paths_ in a network that flow through the node or edge in question.


##### **bipartite (also bimodal) network**


    A network of two _node_ types in which connections are only between nodes of different types. One can perform a _one-mode-projection_ on a bipartite network.


##### **centrality**


    A numerical measurement of the ‘importance’ of a _node_ (or in some cases, an _edge_). _Degree_ is a simple example. See also _betweenness_, _closeness_ _centrality_, _eigenvector_ centrality.


##### **closeness centrality**


    ‘Closeness Centrality measures the proximity of a selected _node_ to all other nodes within the graph’.[^2] It is calculated by taking the reciprocal of the average distance of the node in question to all other nodes in the network. The reciprocal is used in order to ensure that nodes with closer connections to all other nodes have higher values of closeness centrality.


##### **connected component **


    Sometimes also just ‘component’, implying ‘connected’. A connected part of the network. Networks often consist of multiple disjoint connected components.


##### **degree**


    Characteristic of a _node_, counting the number of _edges_ connected to that node. Variants include in-degree and out-degree, which count the number of in-going and out-going edges (respectively) in a _directed network_. Also called degree _centrality_.


##### **directed network**


    A network in which the _edges_ are directional, e.g. when A sends a letter to B.


##### **edge**


    Connection between two _nodes_, sometimes also called _link_, or _arc._ 


##### **eigenvector centrality**


    Eigenvector centrality is a measurement of the structural significance of a _node_ that tries to define a ‘quality’ of a node recursively as a quantity that is proportional to the collective quality of its neighbours in the network. The eigenvector centrality is then given by the stable distribution of quality values on all nodes in the network that obeys this recursive definition.

**force-directed network**


    Force-directed network layouts are a class of algorithm used frequently in visualisation tools like Gephi. In a force-directed layout, each element of the network is modeled as though guided by unseen forces, much as in the physical world: gravity, electromagnetic repulsion, material elasticity. Nodes, for example, may be thought of as electrons on a two-dimensional plane, forcing each other apart as they approach one another. Edges as springs physically anchored between two nodes, drawing them together even as they repulsively push away. 

**idiographic **


    Idiographic and nomothetic are terms introduced by Wilhelm Windelband to distinguish epistemologies rooted in the individual and unique experience from those oriented to general laws. The idiographic approach is associated with the humanities and subjectivity, with a tendency to specify, whereas nomothetic thinking is oriented to the natural sciences and objectivity, with a tendency to generalize.


##### **link**


    See _edge_.


##### **logarithmic**


    If we plot data on a linear scale, values are proportionally spaced: ‘0’, ‘1’, and ‘2’ are equally far apart, and ‘10’ is ten times as far from ‘0’ as ‘1’ is. By contrast, on a logarithmic scale we space things equally if they are related by the same factor. So ‘1’, ‘10’, ‘100’, and ‘1000’ are equally far apart, because they are all related by a factor of 10. We can have a linear scale on one axis and a logarithmic scale on the other, or logarithmic scales on both (often called a log-log plot). See also [Khan Academy's Introduction to Logarithms](https://www.khanacademy.org/math/algebra2/exponential-and-logarithmic-functions/introduction-to-logarithms/a/intro-to-logarithms)_._[^3]


##### **log-log plot**


    A plot with _logarithmic_ scales on both axes. A _scale-free degree distribution_ appears as a straight line on a log-log plot.


##### **matrix**


    A way of representing a network as a table, with a row and a column for each _node_, and values of 0 or 1 in the cells that indicate whether an _edge_ exists (1) or does not exist (0) between a pair of nodes. In a _weighted network_, the edges that exist have the numerical weight of the edge in the cell instead of a 1. For each pair of nodes there are two cells in the matrix, representing the two directions of a possible connection. In an undirected network the values in these two cells have to be the same (making the matrix symmetric), but in a _directed network_ they may differ. Matrices are mathematical objects, and many network analysis algorithms use the matrix representation of a network. Formally a matrix representation of a network is called an _adjacency matrix_. 


##### **multi-partite network**


    A network with more than one _node_ type.


##### **node**


    Sometimes called a _vertex _because it marks the intersection of lines, and sometimes called an _actor_, nodes are the elements of a network that are being connected.

**nomethetic**

	See _idiographic_


##### **PageRank**


    PageRank is a network algorithm used by the company Google to rank search results of webpages. It is a variant of _eigenvector centrality_ and sometimes applied as a _centrality _measure in network analysis.


##### **one-mode projection **


    Transformation of a _bipartite_ network into a _weighted_ network of just one of the two original _node_ types in which the weight of the connection is the number of shared neighbors in the bipartite network. The projection of a bipartite network, in other words, transforms one of the node types into an edge: for example, if we consider a bipartite network of people and the places they have visited, the projection of this network onto people yields a network in which two people are connected to each other if they have visited the same place. If we project the same bipartite network onto places we get a network of places in which two places are connected if at least one person visited both.


##### **power law**


    See _scale-free degree distribution_.


##### **scale-free degree distribution**


    Intuitively one might expect the _degree_ distribution in a network to follow a bell curve, which is more formally described as a normal (or Gaussian) distribution: a large rounded peak around an average value, tapering away rapidly on either side. A power-law degree distribution, by contrast has no peak; instead it decreases continuously and rapidly for increasing degrees. In fact the distribution of the data points within a power-law distribution is very broad, typically spanning several orders of magnitude. It is therefore normally plotted on _logarithmic_ axes (as a _log-log plot_). On these axes a power law distribution appears as a straight diagonal line, which means that the shape of the distribution is the same for high and low degrees, resulting in what is known as a scale-free degree distribution. Whether we look at the network as a whole, or at a specific region, due to the scale-free distribution we will always find a few relatively well-connected _nodes_, or ‘hubs’, and a much larger number of nodes with a relatively small number of connections compared to the hubs. A wide range of networks have been shown to exhibit a scale-free degree distribution, including power grids, social networks, and the world-wide web.


##### **shortest path**


    The shortest path (fewest number of steps) between two _nodes_ in the network.


##### **tie**


    See _edge_.


##### **weighted network**


    A network in which each _edge_ has a numerical weight attached to it, indicating the strength of the connection.


##### **unipartite network**


    A network of just one _node_ type, in contrast to _bipartite_ network. Networks are typically unipartite.


##### **vertex**


    See _node_.


<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     See https://folgerpedia.folger.edu/Glossary_of_network_analysis_terms

[^2]:
     Kevin Cherven, _Mastering Gephi Network Visualization_, (Packt Publishing, 2015)

[^3]:
    https://www.khanacademy.org/math/algebra2/exponential-and-logarithmic-functions/introduction-to-logarithms/a/intro-to-logarithms

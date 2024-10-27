# Social Network Analysis Project

This project was completed as part of the coursework for the course Social Network Analysis during the Bachelor’s degree program in Management and Computer Science at Luiss Guido Carli University. The project is about conducting network analysis in a large network.

The graph we decided to analyze is a huge (1224 nodes liked by 19025 edges) directed-unweighted network of hyperlinks among a large set of U.S. political weblogs from before the 2004 election. It includes blog political affiliation as metadata, where each node represents a political blog and each link represents a reference from one blog to another.

During our researches on the nature of the graph, we discovered that it was the object of an interesting paper in which it is analyzed deeply by Lada A. Adamic and Natalie Glance, "The political blogosphere and the 2004 US Election", in Proceedings of the WWW-2005 Workshop on the Weblogging Ecosystem, 2005 (https://edisciplinas.usp.br/pluginfile.php/3333574/mod_resource/content/2/p36-adamic.pdf).

We also discovered that the data we had are a portion of the original one available online, which is reperible here https://networks.skewed.de/net/polblogs. This more complete dataset (which is located in the folder "Original graph") contains information about a total of 1490 nodes. The additional information we gathered contains the URL of the blog to which each node is related, and a lablel for the political orientation of each node (0 for left or liberal, and 1 for right or conservative). We used this additional information for enhance our analysis.

In our work, we focused on the nodes which have an in-degree or out-degree of at least one (excluding the singletons). The graph we worked on is therefore characterized by 1224 nodes, liked to each other by 19025 edges. The source from wich the dataset is reachable is the following: http://konect.cc/networks/dimacs10-polblogs/.

Below a representation of the Network, which was coloured following the political orientation of the nodes (blue for left or liberal and red for right or conservative), which was obtained by implementing the graph in Gephi and applying the "force Atlas 2" algorithm for the visualization. We can see that the graph is polarized according to the political orientation of nodes.

<img src="graph visualization.png">

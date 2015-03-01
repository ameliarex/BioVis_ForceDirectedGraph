README
---
Lab 6: Force Directed Graph
---
BCB 4002 Tete Zhang

**Visualization Design**

The common variables of the force directed graph are: 

node

	The nodes are read from the data file and are represented each by a black solid circle with radius 3. The nodes have the title of the kinases displayed in the related html file but not necessarily on the visualization.

link	
	
	The links are established by drawing a line connecting the "baits" and the "preys" listed in the database. The style of the links are defined in a css class of stroke #999 and stroke-opacity 0.6. 

charge

	The charge is defined to -30 for proper vision of all nodes. A negative charge results in node repulsion, while a positive charge results in node attraction. 

linkDistance

	linkDistance defines the distance between the nodes. The nodes created in each "tick" is going to adjust their original position to reach the defined distance. 
	
size

	The size of the force defines the area for the relationship of data to be displayed. 
	
tick
	
	Tick runs he force layout simulation for one step. In this graph Tick sets the initial position of the nodes and the links. 
	
**Comparison between the Force Directed Graph and the Original Graph in the Badyophdhyay Paper**

The force directed graph drawn in lab 6 has a clearer expanded view of all kinases in the database. Their connections to each other can be seen clearly comparing to the hairball structure in Figure #3 of the paper. 

However with the support of more data, the original graph had the ability to display the frequency of each bait-prey pair of kinases and have the coloring for different types of kinases. 
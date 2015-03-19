#Overview
D3-Tree-Sim is the simulator of D3-Tree, a Dynamic Distributed Deterministic Load - Balancer for decentralized networks. With respect to its structure, the D3-Tree architecture supports the operations of Join and Departure of nodes. Moreover, the D3-Tree implements an indexing scheme for the stored data, supporting the operations Insert a new element, Delete an existing element, Search for an element and Range Query for elements in a specific range. Last but not least, D3-Tree is highly fault-tolerant, achieving a significant success rate for search operations, even for massive node failures.

#Download and Install
##Download
The simulator is available in D3TREE.zip (requires .NET Framework 4.0 available [here](http://www.microsoft.com/en-au/download/details.aspx?id=17718 "simulator url").
##Installation
The simulator doesn't need any installation. Simply unzip the contents of the D3TREE.zip to a folder of your choice and double-click the executable (.exe) file!

#User Guide
The simulator offers a user-friendly interface and a graphical representation of the structure created.

![Alt text](/ss01.png)
<!--A screenshot is available [https://drive.google.com/file/d/0B7iJDTWTJnCnZ0tQY1gxYV9IS0E/view?usp=sharing here].-->

At the top left, you can construct a new tree after setting the tree parameters.

At the top right, you can conduct experiments, setting the parameters for each one of them. The experiments refer to:
 * node joins/departures,
 * element insertions/deletions,
 * single and range queries, with/without node failures.

In the centre of the screen, useful information is displayed regarding binary nodes, nodes in buckets, tree construction and experiments.

At the bottom, a graphical representation of the structure is displayed.

Reports summarizing experiment results are saved automatically in .csv files into \Logs folder. Whenever a new tree is constructed or a new experiment is conducted, a new .csv file is created. Otherwise, if you repeat the experiment with new parameters, the existing .csv file is updated.

Enjoy!
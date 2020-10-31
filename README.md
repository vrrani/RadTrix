# RadTrix
A Visualization tool for Bi-Partite Network
RadTrix is a composite of two visualizations in a single view, i.e., matrix visualization for smaller (D) set and circular/radial graph layout for the larger (N) set in a bipartite graph.  The layout follows the nesting composite visualization view design.

Reduction in visual clutter is attained 

 -- Using quadratic spatial complexity of matrix and 4 connection points. Choice of connection point for a node pairs using shortest distance.
 
 -- Uniform distribution of N nodes on the circumference of circle

RadTrix is used for a case-study of the disease-gene association network, the diseasome, constructed using the analysis of multi-omics data. The user interactions such as highlight of corresponding node-links and gene nodes on mouse over show the set cardinality, and set constituencies on and off the diagonal, respectively. 

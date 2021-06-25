# Sub-Ontology_Extraction
A Python implementation of the sub-ontology extraction algorithm ([Ranwez et al., 2011](https://hal.archives-ouvertes.fr/hal-00797150)) applied to the movie recommendation explanation domain.

### Overview
The general aim of the algorithm is to extract a relevant sub-ontology from a entire ontology, given a set of relevant nodes as input. As manipulating and exploiting large ontologies and large knowledge graphs might sometimes be inefficient, people may would like to focus more on the most relevant part of the entire ontology which would be much smaller to exploit while perserving as much as possible the information content of the extracted sub-ontology.

### Example illustration
As an example, here we focus on extracting a sub-ontology relevant to the movie domain. Given as input: 1) a set of nodes (i.e. DBpedia categories which are used to directly annotate movies, e.g. French_comedy_films) and 2) the entire DBpedia category knowledge graph (that contains millions of nodes and hierarchical relationships), the goal is to extract a sub-ontology from the entire knowledge graph that are relevant to the movie domain.

### Repository structure
* The "category_tree" folder contains the input file of movie annotations.
* The "sub-ontology-extraction-example" folder contains a concrete python notebook example illustrating the implemention of the algorithm as well as the resulting sub-ontology.

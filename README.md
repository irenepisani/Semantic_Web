University of Pisa, UNIPI \
M.Sc. Computer science, Artificial Intelligence \
Academic year 2021/22 

# Semantic Web

###### Final Exam Project for Semantic Web course

The main aim of the project was to implement an **ontology for narrative domain application**.

`Pisani_SW_Project.owl` contains the ontology written in **OWL 2 DL** using **RDF Turtle notation** and developed with the [Protege Framework](https://protege.stanford.edu/).

All the required **Classes** (C), **Data Properties** (DP) and **Object Properties** (OP) have been declared, providing:
- a textual label and a textual description of the intension of the property, using the appropriate annotation property from the RDFS vocabulary;
- axioms defining domain, range and inverse of the property (inverse only for OP); 
- any additional axioms expressing disjointness of the property with other properties, and the property characteristics;
- any additional axioms expressing disjointness of the classes with other classes;
- sub-property axioms defining the property taxonomy (both for OP and DP) and class taxonomy.
Further required axioms have been defined to express some **facts** characterising this application domain. 
Finally, the ontology has been populated with at least one **individual** for each class and at least one **assertion** for each property.

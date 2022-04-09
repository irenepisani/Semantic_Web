University of Pisa, UNIPI \
M.Sc. Computer science, Artificial Intelligence \
Academic year 2021/22 

# Semantic Web

###### Final Exam Project for Semantic Web course (Prof. Valentina Lenzi Bartalesi)

The main aim of the project was to implement an **ontology for Narrative Domain Application**. \
The [ontology](Pisani_SW_Project.owl) written in **OWL 2 DL** using **RDF Turtle notation** was developed with the [Protege Framework](https://protege.stanford.edu/) and some types of reasoning were performed over it.

Project Delivery: `Exam04-2022.pdf` 

### Knowledge Representation

Given the application domain, all the required **Classes**, **Data Properties** and **Object Properties** have been declared providing:
- a textual label and a textual description of the intension of the property, using the appropriate annotation property from the RDFS vocabulary;
- axioms defining domain, range and inverse of the property; 
- any additional axioms expressing disjointness of the property with other properties, and the property characteristics;
- any additional axioms expressing disjointness of the classes with other classes;
- sub-property axioms defining the property taxonomy and class taxonomy.
Further required axioms have been defined to express some **facts** characterising this application domain. \
Finally, the ontology has been populated with at least one **individual** for each class and at least one **assertion** for each property.

Reference file:`Pisani_SW_Project.owl` 

### Reasoning

Some aspects needed to enable reasoning over the given ontology have also been explored. \
First of all, the **consistency** of the ontology was checked in order to derive implicit knowledge correctly and some **complex roles inclusion axioms** were added to the ontology. \
Then, the axiom closure of the ontology was analysed to check whether it satisfies the **global restrictions** necessary to obtain a decidable language and, finally, the ontology content was explored via **SPARQL queries**.  

Reference file:`Pisani_SW_Report.pdf` 

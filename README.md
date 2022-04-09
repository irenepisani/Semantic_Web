University of Pisa, UNIPI \
M.Sc. Computer science, Artificial Intelligence \
Academic year 2021/22 

# Semantic Web

###### Final Exam Project for Semantic Web course



OWL Ontology
The fundamental concepts in an application domain related to narratives (intended as stories about a specific topic) are: events, characters, objects and locations. Some of the facts that characterise this domain can be stated as follows:
1. A narrative is composed of one or more events.
2. A narrative is composed exclusively of events.
3. Each event occurs in exactly one location.
4. A character can be human or not human.
5. Each location can be a real location or a fictional location.
6. Each character, each location and each object have a name (a string).
7. Each event has at least one participating character or object.
8. Each narrative is created by at least one narrator.
9. The narrator has at least one contract with a publisher.
10. A book reports one or more narratives.
11. A book has a title (a string) and it is identified by an ISBN code (a string).
12. A book has exactly one publisher (that is an organisation). The publisher is identified by a name (a
string) and an ID (a positive integer).
13. A publisher publishes more than one book.
14. Narrative, event, location, character, object, narrator, book, bookshop and publisher are pairwise
disjoint concepts.
The candidate should express all the above statements in an OWL 2 DL ontology, using the RDF Turtle notation. In particular, the ontology must:
Q1. Declare the required classes, providing for each class a textual label and a concise textual description of the intension of the class, using the appropriate annotation properties from the RDF Schema vocabulary
Q2. Provide the sub-class axioms defining the class taxonomy
Q3. Declare the required object properties, providing for each property:
Q.1. a textual label, using the appropriate annotation property from the RDFS vocabulary
Q3.2. a textual description of the intension of the property, using the appropriate annotation property
from the RDFS vocabulary
Q3.3. one axiom defining the domain of the property
Q3.4. one axiom defining the range of the property
Q3.5. one axiom defining the inverse of the property
Q3.6. any additional axioms expressing disjointness of the property with other object properties, and
the property characteristics.
Q4. Provide the sub-property axioms defining the object property taxonomy Q5. Declare the required data properties, providing:
Q5.1. a textual label, using the appropriate annotation property from the RDFS vocabulary
Q5.2. a textual description of the intension of the property, using the appropriate annotation property
from the RDFS vocabulary
Q5.3. one axiom defining the domain of the property
Q5.4. one axiom defining the range of the property
Q5.5. any additional axioms expressing disjointness of the property with other data properties, and
whether the property is functional.
Q6. Define the axioms necessary for expressing any statement in 1 to 14 that has not already been expressed.
Q7. Populate the ontology with at least one individual for each class, and at least one assertion for each
property.

# This repository contains all files relevant to the extention of the Common Greenhouse Ontology (CGO) in OWL.

This repository is structured as follow:

- `./owl`: folder containing the definition files of the ontology.
- `./prototype`: folder containing files to simulate the implementation of the extended CGO
- `./OntoUML`: folder containing OntoUML diagrams describing the domain behind the ontology and its test environment.



Usage of the Prototype:

The prototype is desigend to simulate the functionality of the extended ontology using a Python script. The prototype uses the RDF library to take a set of raw data from the autonomous systems, and apply the new ontology mappings. The raw data is provided as .csv file and outputted as .ttl file, simulating the data-stream from robots to operating system through Callable webserver.

The prototype can be used by simply downloading the 'prototype' folder and running the included python script (Ontology Converter Prototype). This will apply the ontology mappings on the data provided in the test_sheet.csv, creating a .ttl file with the resulting data.




## Authors

- [Tim EICHHORN] - [*@jensreil2001*](https://github.com/jensreil2001) 
- [Ghusen Chalan] - [*@cosina14*](https://github.com/Cosina14)
- [Simon VAN ROOZENDAAL] - [*@Simonvroozendaal*](https://github.com/SimonvRoozendaal)
- [Jens REIL] -[*@T-S-Eichhorn*](https://github.com/T-S-Eichhorn)
- [Jo ̃ao REBELO MOREIRA]
- [Tiago Prince Sales](https://www.researchgate.net/profile/Tiago_Prince_Sales) - [*@tgoprince*](https://github.com/tgoprince)




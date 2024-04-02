# Knowledge Graph for Lifestyle Management in Type 2 Diabetes: User Profiles and Lifestyle Recommendations

The primary objective of this project was to develop a knowledge graph that simplifies the storage of information concerning patients diagnosed with Type 2 Diabetes, facilitating intuitive access and enabling the inference of new information, including tailored lifestyle recommendations for these patients.

* **userKG.owl**: This file contains the finalized ontology with instances and links to external data. Protege is the recommended software tool to open this file.
* **userKG_inferred.rdf**: Included in this file is the same ontology, but with inferred information, obtained after executing the HermiT reasoner.
* **SPARQL.ipynb**: This notebook consists of Python scripts for executing SPARQL queries, utilizing the rdflib library. For usage, upload the "userKG_inferred.rdf" ontology.
* **OntoRandomization.ipynb**: This notebook contains Python scripts for adding patients to the ontology.
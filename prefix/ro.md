---
identifier: MIR:00000120
name: Relation Ontology
description: The OBO Relation Ontology provides consistent and unambiguous formal definitions of the relational expressions used in biomedical ontologies.
prefix: ro
pattern: ^RO_\d+{7}$
prefixed: 0
resources:
 - identifier: MIR:00100764
   accessurl: http://purl.obolibrary.org/obo/${id}
   test_id: RO_0002533
   description: OBO Relation Ontology through OntoBee
   homepage: http://obofoundry.org/ontology/ro.html
   institution: University of Michigan Medical School (MI), Lawrence Berkeley National Laboratory (CA) and Science Commons (MA)
   location: USA
   official: false
 - identifier: MIR:00100767
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ro/terms?short_form=${id}
   test_id: RO_0002533
   description: OBO Relation Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/ro
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

---
identifier: MIR:00000517
name: Mathematical Modelling Ontology
description: The Mathematical Modelling Ontology (MAMO) is a classification of the types of mathematical models used mostly in the life sciences, their variables, relationships and other relevant features.
prefix: mamo
pattern: ^MAMO_\d{7}$
prefixed: 0
resources:
 - identifier: MIR:00100665
   accessurl: http://bioportal.bioontology.org/ontologies/MAMO/?p=classes&conceptid=http://identifiers.org/mamo/${id}
   test_id: MAMO_0000026
   description: MAMO through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/MAMO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100758
   accessurl: http://www.ebi.ac.uk/ols/ontologies/mamo/terms?short_form=${id}
   test_id: MAMO_0000026
   description: MaMO through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/mamo
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

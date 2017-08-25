---
identifier: MIR:00000406
name: VariO
description: The Variation Ontology (VariO) is an ontology for the standardized, systematic description of effects, consequences and mechanisms of variations. It describes the effects of variations at the DNA, RNA and/or protein level.
prefix: vario
pattern: ^VariO:\d+$
prefixed: 0
resources:
 - identifier: MIR:00100526
   accessurl: http://www.variationontology.org/cgi-bin/amivario/term-details.cgi?term=${id}
   test_id: VariO:0294
   description: VariO at Lund University
   homepage: http://www.variationontology.org/
   institution: Department of Experimental Medical Science, Lund University
   location: Sweden
   official: false
 - identifier: MIR:00100566
   accessurl: http://purl.bioontology.org/ontology/VARIO/${id}
   test_id: VariO:0294
   description: VariO through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/VARIO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100677
   accessurl: http://www.ebi.ac.uk/ols/ontologies/vario/terms?obo_id=${id}
   test_id: VariO:0294
   description: VariO through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/vario
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

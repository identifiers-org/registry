---
identifier: MIR:00000002
name: ChEBI
description: Chemical Entities of Biological Interest (ChEBI) is a freely available dictionary of molecular entities focused on 'small' chemical compounds.
prefix: chebi
pattern: ^CHEBI:\d+$
prefixed: 1
resources:
 - identifier: MIR:00100009
   accessurl: http://www.ebi.ac.uk/chebi/searchId.do?chebiId=
   description: ChEBI (Chemical Entities of Biological Interest)
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100158
   accessurl: http://www.ebi.ac.uk/ols/ontologies/chebi/terms?obo_id=
   description: ChEBI through OLS
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100565
   accessurl: http://purl.bioontology.org/ontology/CHEBI/
   description: ChEBI through BioPortal
   location: USA
   official: false
   provider_code: bptl
---

---
identifier: MIR:00000002
name: ChEBI
description: Chemical Entities of Biological Interest (ChEBI) is a freely available dictionary of molecular entities focused on 'small' chemical compounds.
prefix: chebi
pattern: ^CHEBI:\d+$
prefixed: 1
local_id: 36927
resources:
 - identifier: MIR:00100009
   accessurl: http://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:${lid}
   keyword: carbon-14
   description: ChEBI (Chemical Entities of Biological Interest)
   homepage: http://www.ebi.ac.uk/chebi/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100158
   accessurl: http://www.ebi.ac.uk/ols/ontologies/chebi/terms?obo_id=CHEBI:${lid}
   keyword: carbon-14 atom
   description: ChEBI through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/chebi
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100565
   accessurl: http://purl.bioontology.org/ontology/CHEBI/CHEBI:${lid}
   keyword: carbon-14
   description: ChEBI through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/CHEBI
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---

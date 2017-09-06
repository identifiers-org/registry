---
identifier: MIR:00000127
name: Ontology for Biomedical Investigations
description: The Ontology for Biomedical Investigations (OBI) project is developing an integrated ontology for the description of biological and clinical investigations. The ontology will represent the design of an investigation, the protocols and instrumentation used, the material used, the data generated and the type analysis performed on it. Currently OBI is being built under the Basic Formal Ontology (BFO).
prefix: obi
pattern: (^OBI:\d{7}$)|(^OBI_\d{7}$)
prefixed: 0
local_id: OBI:0000070
synonyms:
 - OBI
resources:
 - identifier: MIR:00100162
   accessurl: http://purl.obolibrary.org/obo/${lid}
   keyword: A planned process with the objective to produce
   description: OBI through Ontobee
   homepage: http://www.ontobee.org/
   institution: University of Michigan Medical School (MI), awrence Berkeley National Laboratory (CA) and Science Commons (MA)
   location: USA
   official: true
 - identifier: MIR:00100177
   accessurl: http://purl.bioontology.org/ontology/OBI/${lid}
   keyword: scientific observation
   description: Ontology for Biomedical Investigations through Bioportal
   homepage: http://bioportal.bioontology.org/ontologies/OBI
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100760
   accessurl: http://www.ebi.ac.uk/ols/ontologies/obi/terms?obo_id=${lid}
   keyword: A planned process with the objective to produce
   description: OBI through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/obi
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

---
identifier: MIR:00000081
name: Sequence Ontology
description: The Sequence Ontology (SO) is a structured controlled vocabulary for the parts of a genomic annotation. It provides a common set of terms and definitions to facilitate the exchange, analysis and management of genomic data.
prefix: so
pattern: ^SO:\d{7}$
prefixed: 1
local_id: 0000704
synonyms:
 - SO
 - Sequence Types and Features
resources:
 - identifier: MIR:00100112
   accessurl: http://www.sequenceontology.org/miso/current_release/term/SO:${lid}
   keyword: necessary to encode a functional transcript.
   description: Sequence Ontology
   homepage: http://www.sequenceontology.org/
   institution: Department of Molecular and Cellular Biology, University of California, Berkeley
   location: USA
   official: false
 - identifier: MIR:00100241
   accessurl: http://purl.bioontology.org/ontology/SO/SO:${lid}
   keyword: necessary to encode a functional transcript.
   description: Sequence Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/SO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100628
   accessurl: http://www.ebi.ac.uk/ols/ontologies/so/terms?obo_id=SO:${lid}
   keyword: necessary to encode a functional transcript.
   description: Sequence Ontology through Ontology Lookup Service (OLS)
   homepage: http://www.ebi.ac.uk/ols/ontologies/so
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

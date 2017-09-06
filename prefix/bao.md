---
identifier: MIR:00000597
name: BioAssay Ontology
description: The BioAssay Ontology (BAO) describes chemical biology screening assays and their results including high-throughput screening (HTS) data for the purpose of categorizing assays and data analysis.
prefix: bao
pattern: ^\d{7}$
prefixed: 0
local_id: 0002989
resources:
 - identifier: MIR:00100797
   accessurl: http://bioportal.bioontology.org/ontologies/BAO/bao:BAO_${lid}
   keyword: binding assay
   description: BioAssay Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/BAO/
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100798
   accessurl: http://www.ebi.ac.uk/ols/ontologies/bao/terms?obo_id=BAO:${lid}
   keyword: binding assay
   description: BioAssay Ontology through OLS
   homepage: http://bioportal.bioontology.org/ontologies/BAO/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

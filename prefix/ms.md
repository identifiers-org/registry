---
identifier: MIR:00000590
name: Mass Spectrometry Controlled Vocabulary
description: The PSI-Mass Spectrometry (MS) CV contains all the terms used in the PSI MS-related data standards. The CV contains a logical hierarchical structure to ensure ease of maintenance and the development of software that makes use of complex semantics. The CV contains terms required for a complete description of an MS analysis pipeline used in proteomics, including sample labeling, digestion enzymes, instrumentation parts and parameters, software used for identification and quantification of peptides/proteins and the parameters and scores used to determine their significance.
prefix: ms
pattern: ^MS:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100786
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ms/terms?obo_id=${id}
   test_id: MS:1000001
   description: Mass Spectrometry Controlled Vocabulary through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/ms
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100787
   accessurl: http://purl.bioontology.org/ontology/MS/${id}
   test_id: MS:1000001
   description: Mass Spectrometry Controlled Vocabulary through BioPortal
   homepage: https://bioportal.bioontology.org/ontologies/MS
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---

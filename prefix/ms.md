---
identifier: MIR:00000590
name: Mass Spectrometry Controlled Vocabulary
description: The PSI-Mass Spectrometry (MS) CV contains all the terms used in the PSI MS-related data standards. The CV contains a logical hierarchical structure to ensure ease of maintenance and the development of software that makes use of complex semantics. The CV contains terms required for a complete description of an MS analysis pipeline used in proteomics, including sample labeling, digestion enzymes, instrumentation parts and parameters, software used for identification and quantification of peptides/proteins and the parameters and scores used to determine their significance.
prefix: ms
pattern: ^MS:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100786
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ms/terms?obo_id=
   description: Mass Spectrometry Controlled Vocabulary through OLS
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100787
   accessurl: http://purl.bioontology.org/ontology/MS/
   description: Mass Spectrometry Controlled Vocabulary through BioPortal
   location: USA
   official: false
   provider_code: bptl
---

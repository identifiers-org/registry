---
identifier: MIR:00000349
name: BioProject
description: BioProject provides an organizational framework to access metadata about research projects and the data from the projects that are deposited into different databases. It provides information about a project’s scope, material, objectives, funding source and general relevance categories.
prefix: bioproject
pattern: ^PRJ[DEN][A-Z]\d+$
prefixed: 0
resources:
 - identifier: MIR:00100444
   accessurl: http://trace.ddbj.nig.ac.jp/BPSearch/bioproject?acc=
   description: BioProject at DNA Data Bank of Japan
   location: Japan
   official: false
 - identifier: MIR:00100445
   accessurl: http://www.ncbi.nlm.nih.gov/bioproject?term=
   description: BioProject at NCBI
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100446
   accessurl: http://www.ebi.ac.uk/ena/data/view/
   description: BioProject at European Nucleotide Archive (ENA)
   location: UK
   official: false
   provider_code: ebi
---

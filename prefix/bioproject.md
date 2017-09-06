---
identifier: MIR:00000349
name: BioProject
description: BioProject provides an organizational framework to access metadata about research projects and the data from the projects that are deposited into different databases. It provides information about a project’s scope, material, objectives, funding source and general relevance categories.
prefix: bioproject
pattern: ^PRJ[DEN][A-Z]\d+$
prefixed: 0
local_id: PRJDB3
resources:
 - identifier: MIR:00100444
   accessurl: http://trace.ddbj.nig.ac.jp/BPSearch/bioproject?acc=${lid}
   keyword: To elucidate genomic features of genus Gordonia
   description: BioProject at DNA Data Bank of Japan
   homepage: http://trace.ddbj.nig.ac.jp/bioproject/
   institution: DNA Data Bank of Japan, Shizuoka
   location: Japan
   official: false
 - identifier: MIR:00100445
   accessurl: http://www.ncbi.nlm.nih.gov/bioproject?term=${lid}
   keyword: To elucidate genomic features of genus Gordonia
   description: BioProject at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/bioproject
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100446
   accessurl: http://www.ebi.ac.uk/ena/data/view/${lid}
   keyword: To elucidate genomic features of genus Gordonia
   description: BioProject at European Nucleotide Archive (ENA)
   homepage: http://www.ebi.ac.uk/ena/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

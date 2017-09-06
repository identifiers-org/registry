---
identifier: MIR:00000243
name: Sequence Read Archive
description: The Sequence Read Archive (SRA) stores raw sequencing data from the next generation of sequencing platforms Data submitted to SRA. It is organized using a metadata model consisting of six objects: study, sample, experiment, run, analysis and submission. The SRA study contains high-level information including goals of the study and literature references, and may be linked to the INSDC BioProject database.
prefix: insdc.sra
pattern: ^[SED]R[APRSXZ]\d+$
prefixed: 0
local_id: SRX000007
resources:
 - identifier: MIR:00100312
   accessurl: http://www.ncbi.nlm.nih.gov/sra/${lid}?&report=full
   keyword: SID2748
   description: Sequence Read Archive at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/sra
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100313
   accessurl: http://www.ebi.ac.uk/ena/data/view/${lid}
   keyword: SID2748
   description: European Nucleotide Archive (ENA)
   homepage: http://www.ebi.ac.uk/ena
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100314
   accessurl: http://trace.ddbj.nig.ac.jp/DRASearch/experiment?acc=${lid}
   keyword: SID2748
   description: DDBJ Sequence Read Archive (DRA)
   homepage: http://trace.ddbj.nig.ac.jp/dra/
   institution: DNA Data Bank of Japan, Mishima, Shizuoka
   location: Japan
   official: false
---

---
identifier: MIR:00000243
name: Sequence Read Archive
description: The Sequence Read Archive (SRA) stores raw sequencing data from the next generation of sequencing platforms Data submitted to SRA. It is organized using a metadata model consisting of six objects: study, sample, experiment, run, analysis and submission. The SRA study contains high-level information including goals of the study and literature references, and may be linked to the INSDC BioProject database.
prefix: insdc.sra
pattern: ^[SED]R[APRSXZ]\d+$
prefixed: 0
resources:
 - identifier: MIR:00100312
   accessurl: http://www.ncbi.nlm.nih.gov/sra/
   description: Sequence Read Archive at NCBI
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100313
   accessurl: http://www.ebi.ac.uk/ena/data/view/
   description: European Nucleotide Archive (ENA)
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100314
   accessurl: http://trace.ddbj.nig.ac.jp/DRASearch/experiment?acc=
   description: DDBJ Sequence Read Archive (DRA)
   location: Japan
   official: false
---

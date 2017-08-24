---
identifier: MIR:00000350
name: BioSample
description: The BioSample Database stores information about biological samples used in molecular experiments, such as sequencing, gene expression or proteomics. It includes reference samples, such as cell lines, which are repeatedly used in experiments. Accession numbers for the reference samples will be exchanged with a similar database at NCBI, and DDBJ (Japan). Record access may be affected due to different release cycles and inter-institutional synchronisation.
prefix: biosample
pattern: ^SAM[NED](\w)?\d+$
prefixed: 0
resources:
 - identifier: MIR:00100447
   accessurl: http://www.ebi.ac.uk/biosamples/sample/
   description: BioSample Database at EBI
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100706
   accessurl: http://www.ncbi.nlm.nih.gov/biosample?term=
   description: BioSample at NCBI
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100707
   accessurl: http://trace.ddbj.nig.ac.jp/BSSearch/biosample?acc=
   description: BioSample at DNA Data Bank of Japan
   location: Japan
   official: false
---

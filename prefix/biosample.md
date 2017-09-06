---
identifier: MIR:00000350
name: BioSample
description: The BioSample Database stores information about biological samples used in molecular experiments, such as sequencing, gene expression or proteomics. It includes reference samples, such as cell lines, which are repeatedly used in experiments. Accession numbers for the reference samples will be exchanged with a similar database at NCBI, and DDBJ (Japan). Record access may be affected due to different release cycles and inter-institutional synchronisation.
prefix: biosample
pattern: ^SAM[NED](\w)?\d+$
prefixed: 0
local_id: SAMD00005257
synonyms:
 - BioSDe
 - BioSdn
resources:
 - identifier: MIR:00100447
   accessurl: http://www.ebi.ac.uk/biosamples/sample/${lid}
   keyword: During oncogenic transformation
   description: BioSample Database at EBI
   homepage: http://www.ebi.ac.uk/biosamples/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100706
   accessurl: http://www.ncbi.nlm.nih.gov/biosample?term=${lid}
   keyword: Alistipes putredinis
   description: BioSample at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/biosample
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100707
   accessurl: http://trace.ddbj.nig.ac.jp/BSSearch/biosample?acc=${lid}
   keyword: Homo sapiens
   description: BioSample at DNA Data Bank of Japan
   homepage: http://trace.ddbj.nig.ac.jp/biosample/
   institution: Institution DNA Data Bank of Japan, Shizuoka
   location: Japan
   official: false
---

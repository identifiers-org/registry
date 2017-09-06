---
identifier: MIR:00000039
name: RefSeq
description: The Reference Sequence (RefSeq) collection aims to provide a comprehensive, integrated, non-redundant set of sequences, including genomic DNA, transcript (RNA), and protein products.
prefix: refseq
pattern: ^((AC|AP|NC|NG|NM|NP|NR|NT|NW|XM|XP|XR|YP|ZP)_\d+|(NZ\_[A-Z]{4}\d+))(\.\d+)?$
prefixed: 0
local_id: NP_012345
resources:
 - identifier: MIR:00100067
   accessurl: http://www.ncbi.nlm.nih.gov/entrez/viewer.fcgi?val=${lid}
   keyword: Saccharomyces cerevisiae S288c
   description: The NCBI Reference Sequence database
   homepage: http://www.ncbi.nlm.nih.gov/projects/RefSeq/
   institution: NCBI, NIH, Bethesda, Maryland
   location: USA
   official: false
   provider_code: ncbi
---

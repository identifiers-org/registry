---
identifier: MIR:00000564
name: DASHR
description: DASHR reports the annotation, expression and evidence for specific RNA processing (cleavage specificity scores/entropy) of human sncRNA genes, precursor and mature sncRNA products across different human tissues and cell types. DASHR integrates information from multiple existing annotation resources for small non-coding RNAs, including microRNAs (miRNAs), Piwi-interacting (piRNAs), small nuclear (snRNAs), nucleolar (snoRNAs), cytoplasmic (scRNAs), transfer (tRNAs), tRNA fragments (tRFs), and ribosomal RNAs (rRNAs). These datasets were obtained from non-diseased human tissues and cell types and were generated for studying or profiling small non-coding RNAs. This collection references RNA records.
prefix: dashr
pattern: ^(hsa-(let|mir)-\w+(-\w+)?)|(piR-\d+)|(chr\w+.tRNA\d+-\w+)|(chr\w+.tRNA\d+-\w+-tRF\d)|((SNORD|SNORA|ACA|HBII|HBI|U)(-)?\w+)|(HY\d\+(-L\d+)?)|((LSU|SSU|5S)(-rRNA_Hsa)?(-L\d+)?)$
prefixed: 0
local_id: hsa-mir-200a
synonyms:
 - Database of small human noncoding RNAs
resources:
 - identifier: MIR:00100741
   accessurl: http://lisanwanglab.org/DASHR/entry/${lid}
   keyword: testiculargerm1
   description: DASHR at  University of Pennsylvania
   homepage: http://lisanwanglab.org/DASHR/
   institution: Department of Pathology and Laboratory Medicine, University of Pennsylvania, Philadelphia
   location: USA
   official: false
---

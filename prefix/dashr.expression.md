---
identifier: MIR:00000565
name: DASHR expression
description: DASHR reports the annotation, expression and evidence for specific RNA processing (cleavage specificity scores/entropy) of human sncRNA genes, precursor and mature sncRNA products across different human tissues and cell types. DASHR integrates information from multiple existing annotation resources for small non-coding RNAs, including microRNAs (miRNAs), Piwi-interacting (piRNAs), small nuclear (snRNAs), nucleolar (snoRNAs), cytoplasmic (scRNAs), transfer (tRNAs), tRNA fragments (tRFs), and ribosomal RNAs (rRNAs). These datasets were obtained from non-diseased human tissues and cell types and were generated for studying or profiling small non-coding RNAs. This collection references RNA expression.
prefix: dashr.expression
pattern: ^(hsa-(let|mir)-\w+(-\w+)?)|(piR-\d+)|(chr\w+.tRNA\d+-\w+)|(chr\w+.tRNA\d+-\w+-tRF\d)|((SNORD|SNORA|ACA|HBII|HBI|U)(-)?\w+)|(HY\d\+(-L\d+)?)|((LSU|SSU|5S)(-rRNA_Hsa)?(-L\d+)?)$
prefixed: 0
resources:
 - identifier: MIR:00100742
   accessurl: http://lisanwanglab.org/DASHR/entry/
   description: DASHR expression at University of Pennsylvania
   location: USA
   official: false
---

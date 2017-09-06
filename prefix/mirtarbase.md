---
identifier: MIR:00000562
name: miRTarBase
description: miRTarBase is a database of miRNA-target interactions (MTIs), collected manually from relevant literature, following Natural Language Processing of the text to identify research articles related to functional studies of miRNAs. Generally, the collected MTIs are validated experimentally by reporter assay, western blot, microarray and next-generation sequencing experiments.
prefix: mirtarbase
pattern: ^MIRT\d{6}$
prefixed: 0
local_id: MIRT000002
resources:
 - identifier: MIR:00100739
   accessurl: http://mirtarbase.mbc.nctu.edu.tw/php/detail.php?mirtid=${lid}
   keyword: Homo sapiens miR-20a stem-loop
   description: miRTarBase at National Chiao Tung University
   homepage: http://mirtarbase.mbc.nctu.edu.tw/
   institution: Institute of Bioinformatics and Systems Biology, National Chiao Tung University, Hsinchu
   location: Taiwan
   official: false
---

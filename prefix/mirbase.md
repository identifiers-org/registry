---
identifier: MIR:00000078
name: miRBase Sequence
description: The miRBase Sequence Database is a searchable database of published miRNA sequences and annotation. The data were previously provided by the miRNA Registry. Each entry in the miRBase Sequence database represents a predicted hairpin portion of a miRNA transcript (termed mir in the database), with information on the location and sequence of the mature miRNA sequence (termed miR).
prefix: mirbase
pattern: MI\d{7}
prefixed: 0
local_id: MI0000001
resources:
 - identifier: MIR:00100135
   accessurl: http://www.mirbase.org/cgi-bin/mirna_entry.pl?acc=${lid}
   keyword: Caenorhabditis elegans let-7 stem-loop
   description: miRBase Sequence Database
   homepage: http://www.mirbase.org/
   institution: Faculty of Life Sciences, University of Manchester 
   location: UK
   official: false
---

---
identifier: MIR:00000389
name: KEGG Environ
description: KEGG ENVIRON (renamed from EDRUG) is a collection of crude drugs, essential oils, and other health-promoting substances, which are mostly natural products of plants. It will contain environmental substances and other health-damagine substances as well. Each KEGG ENVIRON entry is identified by the E number and is associated with the chemical component, efficacy information, and source species information whenever applicable.
prefix: kegg.environ
pattern: ^(ev\:)?E\d+$
prefixed: 0
local_id: ev:E00032
synonyms:
 - KEGG
resources:
 - identifier: MIR:00100506
   accessurl: http://www.kegg.jp/entry/${lid}
   keyword: Lauraceae
   description: KEGG ENVIRON Database
   homepage: http://www.genome.jp/kegg/drug/environ.html
   institution: Kyoto University Bioinformatics Center
   location: Japan
   official: true
---

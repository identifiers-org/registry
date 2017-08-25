---
identifier: MIR:00000031
name: Wormpep
description: Wormpep contains the predicted proteins from the Caenorhabditis elegans genome sequencing project.
prefix: wormpep
pattern: ^CE\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100051
   accessurl: http://www.wormbase.org/db/seq/protein?name=WP:${id}
   test_id: CE28239
   description: Wormpep (Master)
   homepage: http://www.wormbase.org/db/seq/protein
   institution: Cold Spring Harbor Laboratory
   location: USA
   official: true
---

---
identifier: MIR:00000288
name: Worfdb
description: WOrfDB (Worm ORFeome DataBase) contains data from the cloning of complete set of predicted protein-encoding Open Reading Frames (ORFs) of Caenorhabditis elegans. This collection describes experimentally defined transcript structures of unverified genes through RACE (Rapid Amplification of cDNA Ends).
prefix: worfdb
pattern: ^\w+(\.\d+)?
prefixed: 0
resources:
 - identifier: MIR:00100370
   accessurl: http://worfdb.dfci.harvard.edu/index.php?search_type=name&page=showresultrc&race_query=${id}
   test_id: T01B6.1
   description: Worm Orf DB at Harvard
   homepage: http://worfdb.dfci.harvard.edu/
   institution: Center for Cancer Systems Biology, Harvard Medical School, Massachusetts
   location: USA
   official: false
---

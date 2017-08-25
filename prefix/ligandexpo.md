---
identifier: MIR:00000062
name: Ligand Expo
description: Ligand Expo is a data resource for finding information about small molecules bound to proteins and nucleic acids.
prefix: ligandexpo
pattern: ^(\w){3}$
prefixed: 0
resources:
 - identifier: MIR:00100090
   accessurl: http://ligand-depot.rutgers.edu/pyapps/ldHandler.py?formid=cc-index-search&target=${id}&operation=ccid
   test_id: ABC
   description: Ligand Expo at RutgersRCSB PDB
   homepage: http://ligand-depot.rutgers.edu/index.html
   institution: Rutgers, The State University of New Jersey
   location: USA
   official: false
   provider_code: rcsb
 - identifier: MIR:00100615
   accessurl: http://ligand-expo.rcsb.org/pyapps/ldHandler.py?formid=cc-index-search&target=${id}&operation=ccid
   test_id: ABC
   description: Ligand Expo at Rutgers
   homepage: http://ligand-expo.rcsb.org/
   institution: Rutgers, The State University of New Jersey
   location: USA
   official: false
---

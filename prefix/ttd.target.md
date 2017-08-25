---
identifier: MIR:00000093
name: TTD Target
description: The Therapeutic Target Database (TTD) is designed to provide information about the known therapeutic protein and nucleic acid targets described in the literature, the targeted disease conditions, the pathway information and the corresponding drugs/ligands directed at each of these targets. Cross-links to other databases are also introduced to facilitate the access of information about the sequence, 3D structure, function, nomenclature, drug/ligand binding properties, drug usage and effects, and related literature for each target.
prefix: ttd.target
pattern: ^TTDS\d+$
prefixed: 0
resources:
 - identifier: MIR:00100124
   accessurl: http://bidd.nus.edu.sg/group/TTD/ZFTTDDetail.asp?ID=${id}
   test_id: TTDS00056
   description: Therapeutic Target Database Target
   homepage: http://bidd.nus.edu.sg/group/ttd/ttd.asp
   institution: Computational Science Department, National University of Singapore
   location: Singapore
   official: false
---

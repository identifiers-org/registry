---
identifier: MIR:00000215
name: HSSP
description: HSSP (homology-derived structures of proteins) is a derived database merging structural (2-D and 3-D) and sequence information (1-D). For each protein of known 3D structure from the Protein Data Bank, the database has a file with all sequence homologues, properly aligned to the PDB protein.
prefix: hssp
pattern: ^\w{4}$
prefixed: 0
resources:
 - identifier: MIR:00100274
   accessurl: ftp://ftp.embl-heidelberg.de/pub/databases/protein_extras/hssp/${id}.hssp.bz2
   test_id: 102l
   description: HSSP at EMBL
   homepage: http://swift.cmbi.kun.nl/swift/hssp/
   institution: Protein Design Group, European Molecular Biology Laboratory, Heidelberg
   location: Germany
   official: false
 - identifier: MIR:00100458
   accessurl: ftp://ftp.cmbi.ru.nl/pub/molbio/data/hssp/${id}.hssp.bz2
   test_id: 102l
   description: HSSP at CMBI
   homepage: ftp://ftp.cmbi.ru.nl/pub/molbio/data/hssp/
   institution: Nijmegen Centre for Molecular Life Sciences, CMBI, Nijmegen
   location: Holland
   official: false
---

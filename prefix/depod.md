---
identifier: MIR:00000428
name: DEPOD
description: The human DEPhOsphorylation Database (DEPOD) contains information on known human active phosphatases and their experimentally verified protein and nonprotein substrates. Reliability scores are provided for dephosphorylation interactions, according to the type of assay used, as well as the number of laboratories that have confirmed such interaction. Phosphatase and substrate entries are listed along with the dephosphorylation site, bioassay type, and original literature, and contain links to other resources.
prefix: depod
pattern: ^[A-Z0-9]+$
prefixed: 0
resources:
 - identifier: MIR:00100551
   accessurl: http://www.koehnlab.de/depod/showp.php?gene=${id}
   test_id: PTPN1
   description: DEPOD at EMBL
   homepage: http://www.koehnlab.de/depod/
   institution: European Molecular Biology Laboratory EMBL, Heidelberg
   location: Germany
   official: false
---

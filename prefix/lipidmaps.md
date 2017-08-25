---
identifier: MIR:00000052
name: LIPID MAPS
description: The LIPID MAPS Lipid Classification System is comprised of eight lipid categories, each with its own subclassification hierarchy. All lipids in the LIPID MAPS Structure Database (LMSD) have been classified using this system and have been assigned LIPID MAPS ID's which reflects their position in the classification hierarchy.
prefix: lipidmaps
pattern: ^LM(FA|GL|GP|SP|ST|PR|SL|PK)[0-9]{4}([0-9a-zA-Z]{4,6})?$
prefixed: 0
resources:
 - identifier: MIR:00100080
   accessurl: http://www.lipidmaps.org/data/LMSDRecord.php?LMID=${id}
   test_id: LMPR0102010012
   description: Department of Bioengineering and the San Diego Supercomputer Center
   homepage: http://www.lipidmaps.org
   institution: University of California, San Diego
   location: USA
   official: false
---

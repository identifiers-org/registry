---
identifier: MIR:00000104
name: Small Molecule Pathway Database
description: The Small Molecule Pathway Database (SMPDB) contains small molecule pathways found in humans, which are presented visually. All SMPDB pathways include information on the relevant organs, subcellular compartments, protein cofactors, protein locations, metabolite locations, chemical structures and protein quaternary structures. Accompanying data includes detailed descriptions and references, providing an overview of the pathway, condition or processes depicted in each diagram.
prefix: smpdb
pattern: ^SMP\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100137
   accessurl: http://smpdb.ca/view/${id}
   test_id: SMP00001
   description: Small Molecule Pathway Database
   homepage: http://www.smpdb.ca/pathways
   institution: University of Alberta, Edmonton, AB
   location: Canada
   official: false
---

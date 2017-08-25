---
identifier: MIR:00000561
name: Electron Microscopy Data Bank
description: The Electron Microscopy Data Bank (EMDB) is a public repository for electron microscopy density maps of macromolecular complexes and subcellular structures. It covers a variety of techniques, including single-particle analysis, electron tomography, and electron (2D) crystallography. The EMDB map distribution format follows the CCP4 definition, which is widely recognized by software packages used by the structural biology community.
prefix: emdb
pattern: ^EMD-\d{4}$
prefixed: 0
resources:
 - identifier: MIR:00100738
   accessurl: http://www.ebi.ac.uk/pdbe/entry/emdb/${id}
   test_id: EMD-1001
   description: EMDB at Protein Data Bank in Europe
   homepage: http://www.ebi.ac.uk/pdbe/emdb/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

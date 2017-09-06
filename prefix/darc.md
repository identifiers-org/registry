---
identifier: MIR:00000366
name: DARC
description: DARC (Database of Aligned Ribosomal Complexes) stores available cryo-EM (electron microscopy) data and atomic coordinates of ribosomal particles from the PDB, which are aligned within a common coordinate system. The aligned coordinate system simplifies direct visualization of conformational changes in the ribosome, such as subunit rotation and head-swiveling, as well as direct comparison of bound ligands, such as antibiotics or translation factors.
prefix: darc
pattern: ^\d+$
prefixed: 0
local_id: 1250
synonyms:
 - Database of Aligned Ribosomal Complexes
resources:
 - identifier: MIR:00100465
   accessurl: http://darcsite.genzentrum.lmu.de/darc/view.php?id=${lid}
   keyword: E. coli signal recognition particle
   description: DARC at University of Munich
   homepage: http://darcsite.genzentrum.lmu.de/darc/index.php
   institution: Gene Center and Department for Biochemistry and Center for integrated Protein Science Munich, University of Munich, Munich
   location: Germany
   official: false
---

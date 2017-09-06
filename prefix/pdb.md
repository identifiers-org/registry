---
identifier: MIR:00000020
name: Protein Data Bank
description: The Protein Data Bank is the single worldwide archive of structural data of biological macromolecules.
prefix: pdb
pattern: ^[0-9][A-Za-z0-9]{3}$
prefixed: 0
local_id: 2gc4
synonyms:
 - PDB
resources:
 - identifier: MIR:00100029
   accessurl: http://www.rcsb.org/pdb/explore/explore.do?structureId=${lid}
   keyword: methylamine dehydrogenase
   description: RCSB PDB
   homepage: http://www.pdb.org/
   institution: Rutgers, The State University of New Jersey
   location: USA
   official: false
   provider_code: rcsb
 - identifier: MIR:00100037
   accessurl: http://www.pdbe.org/${lid}
   keyword: Methylamine dehydrogenase heavy chain
   description: Protein Databank in Europe (PDBe)
   homepage: http://www.pdbe.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: pdbe
 - identifier: MIR:00100096
   accessurl: http://proteopedia.org/wiki/index.php/${lid}
   keyword: Paracoccus denitrificans
   description: Proteopedia
   homepage: http://www.proteopedia.org/
   institution: Weizmann Institute of Science
   location: Israel
   official: false
 - identifier: MIR:00100165
   accessurl: http://pdbj.org/mine/summary/${lid}
   keyword: methylamine dehydrogenase
   description: Protein Data Bank Japan (PDBj)
   homepage: http://www.pdbj.org/
   institution: Institute for Protein Research, Osaka University
   location: Japan
   official: false
   provider_code: pdbj
 - identifier: MIR:00100166
   accessurl: http://www.ebi.ac.uk/pdbsum/${lid}
   keyword: Oxidoreductase, electron transport
   description: Protein Databank through PDBsum
   homepage: http://www.ebi.ac.uk/pdbsum/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

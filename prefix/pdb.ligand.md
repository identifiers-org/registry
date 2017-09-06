---
identifier: MIR:00000490
name: Protein Data Bank Ligand
description: The Protein Data Bank is the single worldwide archive of structural data of biological macromolecules. This collection references ligands.
prefix: pdb.ligand
pattern: ^[A-Za-z0-9]+$
prefixed: 0
local_id: TRQ
resources:
 - identifier: MIR:00100626
   accessurl: http://www.rcsb.org/pdb/ligand/ligandsummary.do?hetId=${lid}
   keyword: L-peptide linking
   description: PDB Ligand at RCSB
   homepage: http://www.pdb.org/
   institution: Rutgers, The State University of New Jersey
   location: USA
   official: false
   provider_code: rcsb
 - identifier: MIR:00100650
   accessurl: http://www.ebi.ac.uk/pdbe-srv/pdbechem/chemicalCompound/show/${lid}
   keyword: L-PEPTIDE LINKING
   description: PDB Ligand at Protein Databank in Europe (PDBe)
   homepage: http://www.pdbe.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
---

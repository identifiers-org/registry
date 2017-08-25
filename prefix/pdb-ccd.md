---
identifier: MIR:00000113
name: Chemical Component Dictionary
description: The Chemical Component Dictionary is as an external reference file describing all residue and small molecule components found in Protein Data Bank entries. It contains detailed chemical descriptions for standard and modified amino acids/nucleotides, small molecule ligands, and solvent molecules. Each chemical definition includes descriptions of chemical properties such as stereochemical assignments, aromatic bond assignments, idealized coordinates, chemical descriptors (SMILES & InChI), and systematic chemical names.
prefix: pdb-ccd
pattern: ^\w{3}$
prefixed: 0
resources:
 - identifier: MIR:00100146
   accessurl: http://www.ebi.ac.uk/pdbe-srv/pdbechem/chemicalCompound/show/${id}
   test_id: AB0
   description: Protein Data Bank Chemical Component Dictionary at EBI
   homepage: http://www.ebi.ac.uk/pdbe-srv/pdbechem/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

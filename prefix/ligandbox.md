---
identifier: MIR:00000477
name: LigandBox
description: LigandBox is a database of 3D compound structures.  Compound information is collected from the catalogues of various commercial suppliers, with approved drugs and biochemical compounds taken from KEGG and PDB databases. Each chemical compound in the database has several 3D conformers with hydrogen atoms and atomic charges, which are ready to be docked into receptors using docking programs. Various physical properties, such as aqueous solubility (LogS) and carcinogenicity have also been calculated to characterize the ADME-Tox properties of the compounds.
prefix: ligandbox
pattern: ^D\d{5}
prefixed: 0
resources:
 - identifier: MIR:00100612
   accessurl: http://ligandbox.protein.osaka-u.ac.jp/ligandbox/cgi-bin/liginf.cgi?id=${id}
   test_id: D00001
   description: LigandBox at
   homepage: http://ligandbox.protein.osaka-u.ac.jp/ligandbox//cgi-bin/index.cgi?LANG=en
   institution: nstitute for Protein Research, Osaka University and Fujitsu Kyushu R&amp;D Center, Life Science Systems Dept., Fujitsu
   location: Japan
   official: false
---

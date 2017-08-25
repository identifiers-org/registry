---
identifier: MIR:00000526
name: Human Proteome Map Protein
description: The Human Proteome Map (HPM) portal integrates the peptide sequencing result from the draft map of the human proteome project. The project was based on LC-MS/MS by utilizing of high resolution and high accuracy Fourier transform mass spectrometry. The HPM contains direct evidence of translation of a number of protein products derived from human genes, based on peptide identifications of multiple organs/tissues and cell types from individuals with clinically defined healthy tissues. The HPM portal provides data on individual proteins, as well as on individual peptide spectra. This collection references proteins.
prefix: hpm.protein
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100682
   accessurl: http://www.humanproteomemap.org/protein.php?hpm_id=${id}
   test_id: 1968
   description: Human Proteome Map Protein at Institute of Bioinformatics (Bangalore)
   homepage: http://www.humanproteomemap.org/index.php
   institution: Institute of Bioinformatics, International Tech Park, Bangalore
   location: India
   official: false
---

---
identifier: MIR:00000527
name: Human Proteome Map Peptide
description: The Human Proteome Map (HPM) portal integrates the peptide sequencing result from the draft map of the human proteome project. The project was based on LC-MS/MS by utilizing of high resolution and high accuracy Fourier transform mass spectrometry. The HPM contains direct evidence of translation of a number of protein products derived from human genes, based on peptide identifications of multiple organs/tissues and cell types from individuals with clinically defined healthy tissues. The HPM portal provides data on individual proteins, as well as on individual peptide spectra. This collection references individual peptides through spectra.
prefix: hpm.peptide
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100683
   accessurl: http://www.humanproteomemap.org/spectrum.php?pep_id=${id}
   test_id: 9606117
   description: Human Proteome Map Peptide at Institute of Bioinformatics (Bangalore)
   homepage: http://www.humanproteomemap.org/index.php
   institution: Institute of Bioinformatics, International Tech Park, Bangalore
   location: India
   official: false
---

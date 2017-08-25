---
identifier: MIR:00000053
name: PeptideAtlas
description: The PeptideAtlas Project provides a publicly accessible database of peptides identified in tandem mass spectrometry proteomics studies and software tools.
prefix: peptideatlas
pattern: ^PAp[0-9]{8}$
prefixed: 0
resources:
 - identifier: MIR:00100081
   accessurl: https://db.systemsbiology.net/sbeams/cgi/PeptideAtlas/Summarize_Peptide?query=QUERY&searchForThis=${id}
   test_id: PAp00000009
   description: PeptideAtlas at ISB
   homepage: http://www.peptideatlas.org/
   institution: Institute for Systems Biology, Seattle
   location: USA
   official: false
---

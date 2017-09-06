---
identifier: MIR:00000061
name: PRINTS
description: PRINTS is a compendium of protein fingerprints. A fingerprint is a group of conserved motifs used to characterise a protein family; its diagnostic power is refined by iterative scanning of a SWISS-PROT/TrEMBL composite. Usually the motifs do not overlap, but are separated along a sequence, though they may be contiguous in 3D-space. Fingerprints can encode protein folds and functionalities more flexibly and powerfully than can single motifs, full diagnostic potency deriving from the mutual context provided by motif neighbours.
prefix: prints
pattern: ^PR\d{5}$
prefixed: 0
local_id: PR00001
synonyms:
 - SPRINT
resources:
 - identifier: MIR:00100089
   accessurl: http://www.bioinf.manchester.ac.uk/cgi-bin/dbbrowser/sprint/searchprintss.cgi?prints_accn=${lid}&display_opts=Prints&category=None&queryform=false&regexpr=off
   keyword: Coagulation factor GLA domain signature
   description: PRINTS through SPRINT
   homepage: http://www.bioinf.manchester.ac.uk/dbbrowser/sprint/
   institution: University of Manchester
   location: United Kingdom
   official: false
---

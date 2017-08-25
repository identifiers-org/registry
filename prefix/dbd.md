---
identifier: MIR:00000455
name: DBD
description: The DBD (transcription factor database) provides genome-wide transcription factor predictions for organisms across the tree of life. The prediction method identifies sequence-specific DNA-binding transcription factors through homology using profile hidden Markov models (HMMs) of domains from Pfam and SUPERFAMILY. It does not include basal transcription factors or chromatin-associated proteins.
prefix: dbd
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100590
   accessurl: http://www.transcriptionfactor.org/index.cgi?Search/Domain+domain:${id}+cat:DBD
   test_id: 0045310
   description: DBD at MRC Laboratory of Molecular Biology
   homepage: http://www.transcriptionfactor.org/
   institution: MRC Laboratory of Molecular Biology, Cambridge
   location: UK
   official: false
---

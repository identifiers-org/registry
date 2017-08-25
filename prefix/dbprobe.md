---
identifier: MIR:00000160
name: dbProbe
description: The NCBI Probe Database is a public registry of nucleic acid reagents designed for use in a wide variety of biomedical research applications, together with information on reagent distributors, probe effectiveness, and computed sequence similarities.
prefix: dbprobe
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100205
   accessurl: http://www.ncbi.nlm.nih.gov/probe/?term=${id}
   test_id: 1000000
   description: dbProbe at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/sites/entrez?db=probe
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---

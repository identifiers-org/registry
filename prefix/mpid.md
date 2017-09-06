---
identifier: MIR:00000124
name: Microbial Protein Interaction Database
description: The microbial protein interaction database (MPIDB) provides physical microbial interaction data. The interactions are manually curated from the literature or imported from other databases, and are linked to supporting experimental evidence, as well as evidences based on interaction conservation, protein complex membership, and 3D domain contacts.
prefix: mpid
pattern: ^\d+$
prefixed: 0
local_id: 1776
synonyms:
 - MPID
resources:
 - identifier: MIR:00100157
   accessurl: http://www.jcvi.org/mpidb/experiment.php?interaction_id=${lid}
   keyword: Thermotoga maritima
   description: Microbial Protein Interaction Database
   homepage: http://www.jcvi.org/mpidb/about.php
   institution: J. Craig Venter Institute, Maryland
   location: USA
   official: false
 - identifier: MIR:00100655
   accessurl: http://www.ebi.ac.uk/intact/query/interaction_id:MPIDB-INT-${lid}
   keyword: spoke expanded co-complexes
   description: Microbial Protein Interaction Database subset through IntAct
   homepage: http://www.ebi.ac.uk/intact/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

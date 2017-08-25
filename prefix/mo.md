---
identifier: MIR:00000303
name: MGED Ontology
description: The MGED Ontology (MO) provides terms for annotating all aspects of a microarray experiment from the design of the experiment and array layout, through to the preparation of the biological sample and the protocols used to hybridize the RNA and analyze the data.
prefix: mo
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100385
   accessurl: http://purl.bioontology.org/ontology/MO/${id}
   test_id: ArrayGroup
   description: MGED Ontology at BioPortal
   homepage: http://bioportal.bioontology.org/
   institution: National Center for Biomedical Ontology, Stanford University
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100568
   accessurl: http://mged.sourceforge.net/ontologies/MGEDontology.php#${id}
   test_id: ArrayGroup
   description: MGED Ontology at SourceForge
   homepage: http://mged.sourceforge.net/ontologies/MGEDontology.php
   institution: (Ontology Working Group), European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

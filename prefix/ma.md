---
identifier: MIR:00000445
name: Mouse Adult Gross Anatomy
description: A structured controlled vocabulary of the adult anatomy of the mouse (Mus)
prefix: ma
pattern: ^MA:\d+$
prefixed: 1
resources:
 - identifier: MIR:00100576
   accessurl: http://purl.bioontology.org/ontology/MA/${id}
   test_id: MA:0002502
   description: Mouse Adult Gross Anatomy through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/MA
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100577
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ma/terms?obo_id=${id}
   test_id: MA:0002502
   description: Mouse Adult Gross Anatomy through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/ma
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100578
   accessurl: http://www.informatics.jax.org/searches/AMA.cgi?id=${id}
   test_id: MA:0002502
   description: Mouse Adult Gross Anatomy at The Jackson Laboratory
   homepage: http://www.informatics.jax.org/
   institution: The Jackson Laboratory, Bar Harbor, Maine
   location: USA
   official: true
---

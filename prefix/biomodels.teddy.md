---
identifier: MIR:00000107
name: TEDDY
description: The Terminology for Description of Dynamics (TEDDY) is an ontology for dynamical behaviours, observable dynamical phenomena, and control elements of bio-models and biological systems in Systems Biology and Synthetic Biology.
prefix: biomodels.teddy
pattern: ^TEDDY_\d{7}$
prefixed: 0
resources:
 - identifier: MIR:00100140
   accessurl: http://purl.bioontology.org/ontology/TEDDY/${id}
   test_id: TEDDY_0000066
   description: TEDDY through BioPortal
   homepage: http://teddyontology.sourceforge.net/
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100761
   accessurl: http://www.ebi.ac.uk/ols/ontologies/teddy/terms?short_form=${id}
   test_id: TEDDY_0000066
   description: TEDDY though OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/teddy
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

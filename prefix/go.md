---
identifier: MIR:00000022
name: Gene Ontology
description: The Gene Ontology project provides a controlled vocabulary to describe gene and gene product attributes in any organism.
prefix: go
pattern: ^GO:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100012
   accessurl: http://www.ebi.ac.uk/QuickGO/GTerm?id=
   description: QuickGO (Gene Ontology browser)
   location: UK
   official: false
   provider_code: quickgo
 - identifier: MIR:00100013
   accessurl: http://amigo.geneontology.org/amigo/term/
   description: AmiGO 2
   location: USA
   official: true
   provider_code: amigo
 - identifier: MIR:00100015
   accessurl: http://www.informatics.jax.org/searches/GO.cgi?id=
   description: GO Browser
   location: USA
   official: false
 - identifier: MIR:00100237
   accessurl: http://purl.bioontology.org/ontology/GO/
   description: GO through BioPortal
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100585
   accessurl: http://www.pantherdb.org/panther/category.do?categoryAcc=
   description: GO through PANTHER
   location: USA
   official: false
 - identifier: MIR:00100675
   accessurl: http://www.ebi.ac.uk/ols/ontologies/go/terms?obo_id=
   description: GO through OLS
   location: UK
   official: false
   provider_code: ols
---

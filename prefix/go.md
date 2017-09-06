---
identifier: MIR:00000022
name: Gene Ontology
description: The Gene Ontology project provides a controlled vocabulary to describe gene and gene product attributes in any organism.
prefix: go
pattern: ^GO:\d{7}$
prefixed: 1
local_id: 0006915
synonyms:
 - GO
resources:
 - identifier: MIR:00100012
   accessurl: http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:${lid}
   keyword: apoptosis
   description: QuickGO (Gene Ontology browser)
   homepage: http://www.ebi.ac.uk/QuickGO/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: quickgo
 - identifier: MIR:00100013
   accessurl: http://amigo.geneontology.org/amigo/term/GO:${lid}
   keyword: apoptotic process
   description: AmiGO 2
   homepage: http://amigo.geneontology.org/
   institution: The Gene Ontology Consortium
   location: USA
   official: true
   provider_code: amigo
 - identifier: MIR:00100015
   accessurl: http://www.informatics.jax.org/searches/GO.cgi?id=GO:${lid}
   keyword: apoptosis
   description: GO Browser
   homepage: http://www.informatics.jax.org/searches/GO_form.shtml
   institution: The Jackson Laboratory
   location: USA
   official: false
 - identifier: MIR:00100237
   accessurl: http://purl.bioontology.org/ontology/GO/GO:${lid}
   keyword: apoptosis
   description: GO through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/GO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100585
   accessurl: http://www.pantherdb.org/panther/category.do?categoryAcc=GO:${lid}
   keyword: reproduction
   description: GO through PANTHER
   homepage: http://www.pantherdb.org/
   institution: Keck School of Medicine, University of Southern California
   location: USA
   official: false
 - identifier: MIR:00100675
   accessurl: http://www.ebi.ac.uk/ols/ontologies/go/terms?obo_id=GO:${lid}
   keyword: apoptosis
   description: GO through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/go
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---

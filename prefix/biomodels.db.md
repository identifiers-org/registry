---
identifier: MIR:00000007
name: BioModels Database
description: BioModels Database is a data resource that allows biologists to store, search and retrieve published mathematical models of biological interests.
prefix: biomodels.db
pattern: ^((BIOMD|MODEL)\d{10})|(BMID\d{12})$
prefixed: 0
resources:
 - identifier: MIR:00100006
   accessurl: http://www.ebi.ac.uk/biomodels-main/
   description: BioModels Database
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100107
   accessurl: http://biomodels.caltech.edu/
   description: Caltech mirror
   location: USA
   official: false
 - identifier: MIR:00100674
   accessurl: http://cu.biomodels.bio2rdf.org/describe/?url=http://bio2rdf.org/biomodels:
   description: Bio2RDF
   location: 
   official: false
---

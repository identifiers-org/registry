---
identifier: MIR:00000084
name: ChEMBL compound
description: ChEMBL is a database of bioactive compounds, their quantitative properties and bioactivities (binding constants, pharmacology and ADMET, etc). The data is abstracted and curated from the primary scientific literature.
prefix: chembl.compound
pattern: ^CHEMBL\d+$
prefixed: 0
resources:
 - identifier: MIR:00100115
   accessurl: https://www.ebi.ac.uk/chembl/compound/inspect/
   description: ChEMBL compound database at EBI
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100484
   accessurl: http://linkedchemistry.info/chembl/chemblid/
   description: ChEMBL compound RDF
   location: The Netherlands
   official: false
 - identifier: MIR:00100744
   accessurl: http://rdf.ebi.ac.uk/resource/chembl/molecule/
   description: ChEMBL compound RDF through EBI RDF Platform
   location: UK
   official: false
---

---
identifier: MIR:00000084
name: ChEMBL compound
description: ChEMBL is a database of bioactive compounds, their quantitative properties and bioactivities (binding constants, pharmacology and ADMET, etc). The data is abstracted and curated from the primary scientific literature.
prefix: chembl.compound
pattern: ^CHEMBL\d+$
prefixed: 0
local_id: CHEMBL308052
resources:
 - identifier: MIR:00100115
   accessurl: https://www.ebi.ac.uk/chembl/compound/inspect/${lid}
   keyword: NCC[C@H](NC(=O)[C@H](Cc1ccc(F)c
   description: ChEMBL compound database at EBI
   homepage: https://www.ebi.ac.uk/chembldb/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100484
   accessurl: http://linkedchemistry.info/chembl/chemblid/${lid}
   keyword: http://linkedchemistry.info/chembl/molecule/m110313
   description: ChEMBL compound RDF
   homepage: https://github.com/egonw/chembl.rdf
   institution: Maastricht University
   location: The Netherlands
   official: false
 - identifier: MIR:00100744
   accessurl: http://rdf.ebi.ac.uk/resource/chembl/molecule/${lid}
   keyword: ChEMBL RDF
   description: ChEMBL compound RDF through EBI RDF Platform
   homepage: https://www.ebi.ac.uk/rdf/services/chembl/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
---

---
identifier: MIR:00000085
name: ChEMBL target
description: ChEMBL is a database of bioactive compounds, their quantitative properties and bioactivities (binding constants, pharmacology and ADMET, etc). The data is abstracted and curated from the primary scientific literature.
prefix: chembl.target
pattern: ^CHEMBL\d+$
prefixed: 0
local_id: CHEMBL3467
resources:
 - identifier: MIR:00100116
   accessurl: https://www.ebi.ac.uk/chembl/target/inspect/${lid}
   keyword: Multidrug resistance protein 1B
   description: ChEMBL targets database at EBI
   homepage: https://www.ebi.ac.uk/chembldb/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100485
   accessurl: http://linkedchemistry.info/chembl/chemblid/${lid}
   keyword: http://linkedchemistry.info/chembl/target/t11031
   description: ChEMBL target RDF
   homepage: https://github.com/egonw/chembl.rdf
   institution: Maastricht University
   location: The Netherlands
   official: false
 - identifier: MIR:00100743
   accessurl: http://rdf.ebi.ac.uk/resource/chembl/target/${lid}
   keyword: ChEMBL RDF
   description: ChEMBL target RDF through EBI RDF Platform
   homepage: http://rdf.ebi.ac.uk/resource/chembl/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
---

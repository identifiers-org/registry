---
identifier: MIR:00000275
name: HomoloGene
description: HomoloGene is a system for automated detection of homologs among the annotated genes of several completely sequenced eukaryotic genomes.
prefix: homologene
pattern: ^\d+$
prefixed: 0
local_id: 1000
resources:
 - identifier: MIR:00100355
   accessurl: http://www.ncbi.nlm.nih.gov/homologene/${lid}
   keyword: conserved in Euteleostomi
   description: Homologene at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/homologene/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: true
   provider_code: ncbi
 - identifier: MIR:00100699
   accessurl: http://homologene.bio2rdf.org/describe/?url=http://bio2rdf.org/homologene:${lid}
   keyword: homologene group 1000
   description: Bio2RDF
   homepage: http://homologene.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---

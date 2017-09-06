---
identifier: MIR:00000069
name: NCBI Gene
description: Entrez Gene is the NCBI's database for gene-specific information, focusing on completely sequenced genomes, those with an active research community to contribute gene-specific information, or those that are scheduled for intense sequence analysis.
prefix: ncbigene
pattern: ^\d+$
prefixed: 0
local_id: 100010
synonyms:
 - Entrez Gene
resources:
 - identifier: MIR:00100099
   accessurl: http://www.ncbi.nlm.nih.gov/gene/${lid}
   keyword: expressed sequence AA589556
   description: Entrez Gene (NCBI)
   homepage: http://www.ncbi.nlm.nih.gov/gene
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: true
   provider_code: ncbi
 - identifier: MIR:00100693
   accessurl: http://ncbigene.bio2rdf.org/describe/?url=http://bio2rdf.org/ncbigene:${lid}
   keyword: expressed sequence AA589556
   description: Bio2RDF
   homepage: http://ncbigene.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---

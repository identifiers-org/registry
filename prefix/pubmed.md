---
identifier: MIR:00000015
name: PubMed
description: PubMed is a service of the U.S. National Library of Medicine that includes citations from MEDLINE and other life science journals for biomedical articles back to the 1950s.
prefix: pubmed
pattern: ^\d+$
prefixed: 0
local_id: 23735196
resources:
 - identifier: MIR:00100023
   accessurl: http://www.ncbi.nlm.nih.gov/pubmed/${lid}
   keyword: Minimum information requested in the annotation of biochemical models
   description: NCBI PubMed
   homepage: http://www.ncbi.nlm.nih.gov/PubMed/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: true
   provider_code: ncbi
 - identifier: MIR:00100064
   accessurl: http://www.hubmed.org/display.cgi?uids=${lid}
   keyword: Minimum information requested in the annotation of biochemical models
   description: HubMed
   homepage: http://www.hubmed.org/
   institution: Alfred D. Eaton
   location: United Kingdom
   official: false
   provider_code: hubmed
 - identifier: MIR:00100497
   accessurl: http://europepmc.org/abstract/MED/${lid}
   keyword: Minimum information requested in the annotation of biochemical models
   description: Europe PMC
   homepage: http://europepmc.org/
   institution: Europe PubMed Central partners
   location: UK
   official: false
   provider_code: epmc
 - identifier: MIR:00100702
   accessurl: http://pubmed.bio2rdf.org/describe/?url=http://bio2rdf.org/pubmed:${lid}
   keyword: pubmed:23735196
   description: Bio2RDF
   homepage: http://pubmed.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
 - identifier: MIR:00100745
   accessurl: http://linkedlifedata.com/resource/pubmed/id/${lid}
   keyword: PMID
   description: PubMed through Linkedlife data
   homepage: http://linkedlifedata.com/
   institution: Linkedlifedata, Ontotext, Sofia
   location: Bulgaria
   official: false
---

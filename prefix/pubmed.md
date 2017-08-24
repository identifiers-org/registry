---
identifier: MIR:00000015
name: PubMed
description: PubMed is a service of the U.S. National Library of Medicine that includes citations from MEDLINE and other life science journals for biomedical articles back to the 1950s.
prefix: pubmed
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100023
   accessurl: http://www.ncbi.nlm.nih.gov/pubmed/
   description: NCBI PubMed
   location: USA
   official: true
   provider_code: ncbi
 - identifier: MIR:00100064
   accessurl: http://www.hubmed.org/display.cgi?uids=
   description: HubMed
   location: United Kingdom
   official: false
   provider_code: hubmed
 - identifier: MIR:00100497
   accessurl: http://europepmc.org/abstract/MED/
   description: Europe PMC
   location: UK
   official: false
   provider_code: epmc
 - identifier: MIR:00100702
   accessurl: http://pubmed.bio2rdf.org/describe/?url=http://bio2rdf.org/pubmed:
   description: Bio2RDF
   location: 
   official: false
 - identifier: MIR:00100745
   accessurl: http://linkedlifedata.com/resource/pubmed/id/
   description: PubMed through Linkedlife data
   location: Bulgaria
   official: false
---

---
identifier: MIR:00000220
name: Orphanet
description: Orphanet is a reference portal for information on rare diseases and orphan drugs. It’s aim is to help improve the diagnosis, care and treatment of patients with rare diseases.
prefix: orphanet
pattern: ^\d+$
prefixed: 0
local_id: 85163
synonyms:
 - Orpha
resources:
 - identifier: MIR:00100279
   accessurl: http://www.orpha.net/consor/cgi-bin/OC_Exp.php?Lng=EN&Expert=${lid}
   keyword: Hypomyelination-congenital cataract
   description: Orphanet at Inserm
   homepage: http://www.orpha.net/consor/
   institution: Inserm, Hôpital Broussais, Paris
   location: France
   official: true
 - identifier: MIR:00100701
   accessurl: http://orphanet.bio2rdf.org/describe/?url=http://bio2rdf.org/orphanet:${lid}
   keyword: LEUKODYSTROPHY, HYPOMYELINATING
   description: Bio2RDF
   homepage: http://orphanet.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---

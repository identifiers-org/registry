---
identifier: MIR:00000220
name: Orphanet
description: Orphanet is a reference portal for information on rare diseases and orphan drugs. It’s aim is to help improve the diagnosis, care and treatment of patients with rare diseases.
prefix: orphanet
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100279
   accessurl: http://www.orpha.net/consor/cgi-bin/OC_Exp.php?Lng=EN&Expert=${id}
   test_id: 85163
   description: Orphanet at Inserm
   homepage: http://www.orpha.net/consor/
   institution: Inserm, Hôpital Broussais, Paris
   location: France
   official: true
 - identifier: MIR:00100701
   accessurl: http://orphanet.bio2rdf.org/describe/?url=http://bio2rdf.org/orphanet:${id}
   test_id: 85163
   description: Bio2RDF
   homepage: http://orphanet.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---

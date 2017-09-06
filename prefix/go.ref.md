---
identifier: MIR:00000450
name: Gene Ontology Reference
description: The GO reference collection is a set of abstracts that can be cited in the GO ontologies (e.g. as dbxrefs for term definitions) and annotation files (in the Reference column). It provides two types of reference; It can be used to provide details of why specific Evidence codes (see http://identifiers.org/eco/) are assigned, or to present abstract-style descriptions of "GO content" meetings at which substantial changes in the ontologies are discussed and made.
prefix: go.ref
pattern: ^GO_REF:\d{7}$
prefixed: 0
local_id: GO_REF:0000041
synonyms:
 - GO reference collection
resources:
 - identifier: MIR:00100584
   accessurl: http://www.geneontology.org/cgi-bin/references.cgi#${lid}
   keyword: Gene Ontology annotation based on UniPathway vocabulary mapping
   description: Gene Ontology Reference at The Gene Ontology Consortium
   homepage: http://www.geneontology.org/cgi-bin/references.cgi
   institution: The Gene Ontology Consortium
   location: USA
   official: false
---

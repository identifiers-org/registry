---
identifier: MIR:00000265
name: STRING
description: STRING (Search Tool for Retrieval of Interacting Genes/Proteins) is a database of known and predicted protein interactions.
The interactions include direct (physical) and indirect (functional) associations; they are derived from four sources:Genomic Context, High-throughput Experiments,(Conserved) Coexpression, Previous Knowledge. STRING quantitatively integrates interaction data from these sources for a large number of organisms, and transfers information between these organisms where applicable.
prefix: string
pattern: ^([A-N,R-Z][0-9][A-Z][A-Z, 0-9][A-Z, 0-9][0-9])|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9])|([0-9][A-Za-z0-9]{3})$
prefixed: 0
resources:
 - identifier: MIR:00100341
   accessurl: http://string.embl.de/interactions/
   description: STRING at Heidelberg
   location: Germany
   official: false
 - identifier: MIR:00100342
   accessurl: http://string-db.org/interactions/
   description: STRING Mirror at Heidelberg
   location: Germany
   official: false
---

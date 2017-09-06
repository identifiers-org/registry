---
identifier: MIR:00000023
name: SGD
description: The Saccharomyces Genome Database (SGD) project collects information and maintains a database of the molecular biology of the yeast Saccharomyces cerevisiae.
prefix: sgd
pattern: ^((S\d+$)|(Y[A-Z]{2}\d{3}[a-zA-Z](\-[A-Z])?))$
prefixed: 0
local_id: S000006169
synonyms:
 - Saccharomyces Genome Database
resources:
 - identifier: MIR:00100033
   accessurl: http://www.yeastgenome.org/cgi-bin/locus.fpl?dbid=${lid}
   keyword: ARS1020
   description: SGD
   homepage: http://www.yeastgenome.org/
   institution: Stanford University
   location: USA
   official: true
 - identifier: MIR:00100703
   accessurl: http://sgd.bio2rdf.org/describe/?url=http://bio2rdf.org/sgd:${lid}
   keyword: DNA-binding transcription factor
   description: Bio2RDF
   homepage: http://sgd.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---

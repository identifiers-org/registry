---
identifier: MIR:00000023
name: SGD
description: The Saccharomyces Genome Database (SGD) project collects information and maintains a database of the molecular biology of the yeast Saccharomyces cerevisiae.
prefix: sgd
pattern: ^((S\d+$)|(Y[A-Z]{2}\d{3}[a-zA-Z](\-[A-Z])?))$
prefixed: 0
resources:
 - identifier: MIR:00100033
   accessurl: http://www.yeastgenome.org/cgi-bin/locus.fpl?dbid=${id}
   test_id: S000028457
   description: SGD
   homepage: http://www.yeastgenome.org/
   institution: Stanford University
   location: USA
   official: true
 - identifier: MIR:00100703
   accessurl: http://sgd.bio2rdf.org/describe/?url=http://bio2rdf.org/sgd:${id}
   test_id: S000006169
   description: Bio2RDF
   homepage: http://sgd.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---

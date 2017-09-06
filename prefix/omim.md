---
identifier: MIR:00000016
name: OMIM
description: Online Mendelian Inheritance in Man is a catalog of human genes and genetic disorders.
prefix: omim
pattern: ^[*#+%^]?\d{6}$
prefixed: 0
local_id: 603903
synonyms:
 - Online Mendelian Inheritance in Man
 - Mendelian Inheritance in Man
 - MIM
resources:
 - identifier: MIR:00100024
   accessurl: http://omim.org/entry/${lid}
   keyword: SICKLE CELL ANEMIA
   description: OMIM at John Hopkins
   homepage: http://omim.org/
   institution: Johns Hopkins University, Baltimore, Maryland
   location: USA
   official: true
 - identifier: MIR:00100694
   accessurl: http://omim.bio2rdf.org/describe/?url=http://bio2rdf.org/omim:${lid}
   keyword: Scriver and Waugh
   description: Bio2RDF
   homepage: http://omim.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
 - identifier: MIR:00100777
   accessurl: http://mirror.omim.org/entry/${lid}
   keyword: SICKLE CELL ANEMIA
   description: OMIM mirror at John Hopkins
   homepage: http://mirror.omim.org/
   institution: Johns Hopkins University, Baltimore, Maryland
   location: USA
   official: false
---

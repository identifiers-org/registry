---
identifier: MIR:00000011
name: InterPro
description: InterPro is a database of protein families, domains and functional sites in which identifiable features found in known proteins can be applied to unknown protein sequences.
prefix: interpro
pattern: ^IPR\d{6}$
prefixed: 0
resources:
 - identifier: MIR:00100018
   accessurl: http://www.ebi.ac.uk/interpro/entry/${id}
   test_id: IPR000100
   description: InterPro
   homepage: http://www.ebi.ac.uk/interpro/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100697
   accessurl: http://interpro.bio2rdf.org/describe/?url=http://bio2rdf.org/interpro:${id}
   test_id: IPR000100
   description: Bio2RDF
   homepage: http://interpro.bio2rdf.org/fct/
   institution: Bio2RDF.org
   location: 
   official: false
---

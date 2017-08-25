---
identifier: MIR:00000599
name: Identifiers.org Registry
description: The Identifiers.org registry contains registered namespace and provider prefixes with associated access URIs for a large number of high quality data collections. These prefixes are used in web resolution of compact identifiers of the form “PREFIX:ACCESSION” or "PROVIDER/PREFIX:ACCESSION” commonly used to specify bioinformatics and other data resources.
prefix: mir
pattern: ^MIR:\d{8}$
prefixed: 1
resources:
 - identifier: MIR:00100800
   accessurl: http://identifiers.org/registry?query="${id}"
   test_id: MIR:00100037
   description: Identifiers.org Registry through EBI
   homepage: http://identifiers.org/registry
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---

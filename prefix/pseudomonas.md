---
identifier: MIR:00000180
name: Pseudomonas Genome Database
description: The Pseudomonas Genome Database is a resource for peer-reviewed, continually updated annotation for all Pseudomonas species. It includes gene and protein sequence information, as well as regulation and predicted function and annotation.
prefix: pseudomonas
pattern: ^P\w+$
prefixed: 0
resources:
 - identifier: MIR:00100226
   accessurl: http://v2.pseudomonas.com/getAnnotation.do?locusID=${id}
   test_id: PSEEN0001
   description: Pseudomonas Genome Database at Simon Fraser University
   homepage: http://www.pseudomonas.com/
   institution: Simon Fraser University, British Columbia
   location: Canada
   official: false
---

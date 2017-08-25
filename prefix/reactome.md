---
identifier: MIR:00000018
name: Reactome
description: The Reactome project is a collaboration to develop a curated resource of core pathways and reactions in human biology.
prefix: reactome
pattern: (^R-[A-Z]{3}-\d+(-\d+)?(\.\d+)?$)|(^REACT_\d+(\.\d+)?$)
prefixed: 0
resources:
 - identifier: MIR:00100026
   accessurl: http://reactome.org/content/detail/${id}
   test_id: R-HSA-201451
   description: Reactome, a curated knowledgebase of biological pathways
   homepage: http://www.reactome.org/
   institution: Ontario Institute for Cancer Research, NYU Medical School, Cold Spring Harbor Laboratory and European Bioinformatics Institute
   location: Canada / USA / UK
   official: false
---

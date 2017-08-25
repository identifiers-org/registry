---
identifier: MIR:00000035
name: arXiv
description: arXiv is an e-print service in the fields of physics, mathematics, non-linear science, computer science, and quantitative biology.
prefix: arxiv
pattern: ^(\w+(\-\w+)?(\.\w+)?/)?\d{4,7}(\.\d{4}(v\d+)?)?$
prefixed: 0
resources:
 - identifier: MIR:00100060
   accessurl: http://arxiv.org/abs/${id}
   test_id: 0807.4956v1
   description: Cornell University arXiv
   homepage: http://arxiv.org/
   institution: Cornell University
   location: USA
   official: false
---

---
identifier: MIR:00000475
name: KEGG Disease
description: The KEGG DISEASE database is a collection of disease entries capturing knowledge on genetic and environmental perturbations. Each disease entry contains a list of known genetic factors (disease genes), environmental factors, diagnostic markers, and therapeutic drugs. Diseases are viewed as perturbed states of the molecular system, and drugs as perturbants to the molecular system.
prefix: kegg.disease
pattern: ^H\d+$
prefixed: 0
resources:
 - identifier: MIR:00100610
   accessurl: http://www.kegg.jp/entry/${id}
   test_id: H00076
   description: KEGG Disease at Kyoto University Bioinformatics Center
   homepage: http://www.genome.jp/kegg/disease/
   institution: Kyoto University Bioinformatics Center, Kyoto
   location: Japan
   official: true
---

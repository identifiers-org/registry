---
identifier: MIR:00000327
name: UM-BBD Pathway
description: The University of Minnesota Biocatalysis/Biodegradation Database (UM-BBD) contains information on microbial biocatalytic reactions and biodegradation pathways for primarily xenobiotic, chemical compounds. The goal of the UM-BBD is to provide information on microbial enzyme-catalyzed reactions that are important for biotechnology. This collection refers to pathway information.
prefix: umbbd.pathway
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100420
   accessurl: http://umbbd.ethz.ch/servlets/pageservlet?ptype=p&pathway_abbr=${id}
   test_id: ala
   description: Biocatalysis/Biodegradation Database Mirror (Pathway) at ETH Zurich
   homepage: http://umbbd.ethz.ch/
   institution: ETH, Zurich
   location: Switzerland
   official: false
---

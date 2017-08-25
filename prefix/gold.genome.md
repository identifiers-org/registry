---
identifier: MIR:00000401
name: GOLD genome
description: The GOLD (Genomes OnLine Database)is a resource for centralized monitoring of genome and metagenome projects worldwide. It stores information on complete and ongoing projects, along with their associated metadata. This collection references the sequencing status of individual genomes.
prefix: gold.genome
pattern: ^[Gi|Gc]\d+$
prefixed: 0
resources:
 - identifier: MIR:00100521
   accessurl: http://www.genomesonline.org/cgi-bin/GOLD/GOLDCards.cgi?goldstamp=${id}
   test_id: Gi07796
   description: GOLD genome at Department of Energy Joint Genome Institute
   homepage: http://www.genomesonline.org/cgi-bin/GOLD/index.cgi
   institution: Department of Energy Joint Genome Institute, Microbial Genomics and Metagenomics Program, California
   location: USA
   official: false
---

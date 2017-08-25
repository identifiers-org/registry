---
identifier: MIR:00000048
name: TAIR Protein
description: The Arabidopsis Information Resource (TAIR) maintains a database of genetic and molecular biology data for the model higher plant Arabidopsis thaliana. This provides protein information for a given gene model and provides links to other sources such as UniProtKB and GenPept
prefix: tair.protein
pattern: ^AASequence:\d{10}$
prefixed: 0
resources:
 - identifier: MIR:00100076
   accessurl: http://arabidopsis.org/servlets/TairObject?accession=${id}
   test_id: AASequence:1009107926
   description: The Arabidopsis Information Resource (TAIR) Protein
   homepage: http://arabidopsis.org/index.jsp
   institution: Carnegie Institution of Washington Department of Plant Biology and National Center for Genome Resources (NCGR)
   location: USA
   official: false
---

---
identifier: MIR:00000049
name: TAIR Gene
description: The Arabidopsis Information Resource (TAIR) maintains a database of genetic and molecular biology data for the model higher plant Arabidopsis thaliana. This is the reference gene model for a given locus.
prefix: tair.gene
pattern: ^Gene:\d{7}$
prefixed: 0
resources:
 - identifier: MIR:00100077
   accessurl: http://arabidopsis.org/servlets/TairObject?accession=${id}
   test_id: Gene:2200934
   description: The Arabidopsis Information Resource (TAIR) Gene
   homepage: http://arabidopsis.org/index.jsp
   institution: Carnegie Institution of Washington Department of Plant Biology and National Center for Genome Resources (NCGR)
   location: USA
   official: false
---

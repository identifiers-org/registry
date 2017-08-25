---
identifier: MIR:00000588
name: LINCS Data
description: The Library of Network-Based Cellular Signatures (LINCS) Program aims to create a network-based understanding of biology by cataloguing changes in gene expression and other cellular processes that occur when cells are exposed to perturbing agents. The data is organized and available as datasets, each including experimental data, metadata and a description of the dataset and assay. The dataset group comprises datasets for the same experiment but with different data level results (data processed to a different level).
prefix: lincs.data
pattern: ^LD[SG]-\d+$
prefixed: 0
resources:
 - identifier: MIR:00100785
   accessurl: http://lincsportal.ccs.miami.edu/datasets/#/view/${id}
   test_id: LDS-1110
   description: LINCS Data at University of Miami
   homepage: http://lincsportal.ccs.miami.edu/datasets/
   institution: University of Miami, BD2K-LINCS DCIC
   location: USA
   official: false
---

---
identifier: MIR:00000312
name: TreeBASE
description: TreeBASE is a relational database designed to manage and explore information on phylogenetic relationships. It includes phylogenetic trees and data matrices, together with information about the relevant publication, taxa, morphological and sequence-based characters, and published analyses. Data in TreeBASE are exposed to the public if they are used in a publication that is in press or published in a peer-reviewed scientific journal, etc.
prefix: treebase
pattern: ^TB[1,2]?:[A-Z][a-z]?\d+$
prefixed: 0
resources:
 - identifier: MIR:00100395
   accessurl: http://purl.org/phylo/treebase/phylows/study/${id}?format=html
   test_id: TB2:S1000
   description: TreeBASE (hosted at National Evolutionary Synthesis Center)
   homepage: http://treebase.org/
   institution: Phyloinformatics Research Foundation, Durham, North Carolina
   location: USA
   official: false
---

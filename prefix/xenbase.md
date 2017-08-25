---
identifier: MIR:00000186
name: Xenbase
description: Xenbase is the model organism database for Xenopus laevis and X. (Silurana) tropicalis. It contains genomic, development data and community information for Xenopus research. it includes gene expression patterns that incorporates image data from the literature, large scale screens and community submissions.
prefix: xenbase
pattern: ^(XB-GENE-)?\d+$
prefixed: 0
resources:
 - identifier: MIR:00100232
   accessurl: http://www.xenbase.org/gene/showgene.do?method=displayGeneSummary&geneId=${id}
   test_id: 922462
   description: Xenbase at University of Calgary
   homepage: http://www.xenbase.org/
   institution: Department of Biological Sciences, University of Calgary, Alberta
   location: Canada
   official: false
---

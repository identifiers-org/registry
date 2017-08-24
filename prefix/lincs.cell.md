---
identifier: MIR:00000544
name: LINCS Cell
description: The Library of Network-Based Cellular Signatures (LINCS) Program aims to  create a network-based understanding of biology by cataloging changes in gene expression and other cellular processes that occur when cells are exposed to a variety of perturbing agents. The LINCS cell model system can have the following cell categories: cell lines, primary cells, induced pluripotent stem cells, differentiated cells, and embryonic stem cells. The metadata contains information provided by each LINCS Data and Signature Generation Center (DSGC) and the association with a tissue or organ from which the cells were derived, in many cases are also associated to a disease.
prefix: lincs.cell
pattern: (^LCL-\d+{4}$)|(^LDC-\d+{4}$)|(^ES-\d+{4}$)|(^LSC-\d+{4}$)|(^LPC-\d+{4}$)
prefixed: 0
resources:
 - identifier: MIR:00100721
   accessurl: http://lincsportal.ccs.miami.edu/cells/#/view/
   description: LINCS Portal
   location: USA
   official: false
---

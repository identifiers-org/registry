---
identifier: MIR:00000529
name: ZINC
description: ZINC is a free public resource for ligand discovery. The database contains over twenty million commercially available molecules in biologically relevant representations that may be downloaded in popular ready-to-dock formats and subsets. The Web site enables searches by structure, biological activity, physical property, vendor, catalog number, name, and CAS number.
prefix: zinc
pattern: ^(ZINC)?\d+$
prefixed: 0
resources:
 - identifier: MIR:00100688
   accessurl: http://zinc15.docking.org/substances/${id}
   test_id: ZINC1084
   description: ZINC at University of California (San Francisco)
   homepage: http://zinc15.docking.org/
   institution: Shoichet Laboratory, Department of Pharmaceutical Chemistry, University of California, San Francisco
   location: USA
   official: true
---

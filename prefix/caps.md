---
identifier: MIR:00000396
name: CAPS-DB
description: CAPS-DB is a structural classification of helix-cappings or caps compiled from protein structures. The regions of the polypeptide chain immediately preceding or following an alpha-helix are known as Nt- and Ct cappings, respectively. Caps extracted from protein structures have been structurally classified based on geometry and conformation and organized in a tree-like hierarchical classification where the different levels correspond to different properties of the caps.
prefix: caps
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100516
   accessurl: http://www.bioinsilico.org/cgi-bin/CAPSDB/getCAPScluster?nidcl=${id}
   test_id: 434
   description: CAPS-DB at Leeds Institute of Molecular Medicine
   homepage: http://www.bioinsilico.org/cgi-bin/CAPSDB/staticHTML/home
   institution: Leeds Institute of Molecular Medicine, Section of Experimental Therapeutics, University of Leeds, Leeds
   location: UK
   official: false
---

---
identifier: MIR:00000004
name: Enzyme Nomenclature
description: The Enzyme Classification contains the recommendations of the Nomenclature Committee of the International Union of Biochemistry and Molecular Biology on the nomenclature and classification of enzyme-catalysed reactions.
prefix: ec-code
pattern: ^\d+\.-\.-\.-|\d+\.\d+\.-\.-|\d+\.\d+\.\d+\.-|\d+\.\d+\.\d+\.(n)?\d+$
prefixed: 0
resources:
 - identifier: MIR:00100001
   accessurl: http://www.ebi.ac.uk/intenz/query?cmd=SearchEC&ec=
   description: IntEnZ (Integrated relational Enzyme database)
   location: UK
   official: false
   provider_code: intenz
 - identifier: MIR:00100002
   accessurl: http://www.genome.jp/dbget-bin/www_bget?ec:
   description: KEGG Ligand Database for Enzyme Nomenclature
   location: Japan
   official: false
 - identifier: MIR:00100003
   accessurl: http://enzyme.expasy.org/EC/
   description: Enzyme nomenclature database, ExPASy (Expert Protein Analysis System)
   location: Switzerland
   official: false
   provider_code: expasy
 - identifier: MIR:00100308
   accessurl: http://www.enzyme-database.org/query.php?ec=
   description: ExploreEnz at Trinity College
   location: Ireland
   official: false
   provider_code: expenz
---

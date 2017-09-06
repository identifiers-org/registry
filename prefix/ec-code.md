---
identifier: MIR:00000004
name: Enzyme Nomenclature
description: The Enzyme Classification contains the recommendations of the Nomenclature Committee of the International Union of Biochemistry and Molecular Biology on the nomenclature and classification of enzyme-catalysed reactions.
prefix: ec-code
pattern: ^\d+\.-\.-\.-|\d+\.\d+\.-\.-|\d+\.\d+\.\d+\.-|\d+\.\d+\.\d+\.(n)?\d+$
prefixed: 0
local_id: 1.1.1.1
synonyms:
 - Enzyme Classification
 - EC code
 - EC
resources:
 - identifier: MIR:00100001
   accessurl: http://www.ebi.ac.uk/intenz/query?cmd=SearchEC&ec=${lid}
   keyword: Alcohol dehydrogenase
   description: IntEnZ (Integrated relational Enzyme database)
   homepage: http://www.ebi.ac.uk/intenz/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: intenz
 - identifier: MIR:00100002
   accessurl: http://www.genome.jp/dbget-bin/www_bget?ec:${lid}
   keyword: alcohol dehydrogenase
   description: KEGG Ligand Database for Enzyme Nomenclature
   homepage: http://www.genome.jp/dbget-bin/www_bfind?enzyme
   institution: Kyoto University Bioinformatics Center
   location: Japan
   official: false
 - identifier: MIR:00100003
   accessurl: http://enzyme.expasy.org/EC/${lid}
   keyword: Alcohol dehydrogenase
   description: Enzyme nomenclature database, ExPASy (Expert Protein Analysis System)
   homepage: http://enzyme.expasy.org/
   institution: Swiss Institute of Bioinformatics
   location: Switzerland
   official: false
   provider_code: expasy
 - identifier: MIR:00100308
   accessurl: http://www.enzyme-database.org/query.php?ec=${lid}
   keyword: alcohol dehydrogenase
   description: ExploreEnz at Trinity College
   homepage: http://www.enzyme-database.org/
   institution: Trinity College, Dublin
   location: Ireland
   official: false
   provider_code: expenz
---

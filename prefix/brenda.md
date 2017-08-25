---
identifier: MIR:00000071
name: BRENDA
description: BRENDA is a collection of enzyme functional data available to the scientific community. Data on enzyme function are extracted directly from the primary literature The database covers information on classification and nomenclature, reaction and specificity, functional parameters, occurrence, enzyme structure and stability, mutants and enzyme engineering, preparation and isolation, the application of enzymes, and ligand-related data.
prefix: brenda
pattern: ^((\d+\.-\.-\.-)|(\d+\.\d+\.-\.-)|(\d+\.\d+\.\d+\.-)|(\d+\.\d+\.\d+\.\d+))$
prefixed: 0
resources:
 - identifier: MIR:00100101
   accessurl: http://www.brenda-enzymes.org/php/result_flat.php4?ecno=${id}
   test_id: 1.1.1.1
   description: Brenda enzyme database
   homepage: http://www.brenda-enzymes.org/
   institution: Technical University Braunschweig, Institute for Bioinformatics and Biochemistry
   location: Germany
   official: false
---

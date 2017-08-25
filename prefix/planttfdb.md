---
identifier: MIR:00000579
name: Plant Transcription Factor Database
description: The Plant TF database (PlantTFDB) systematically identifies transcription factors for plant species. It includes annotation for identified TFs, including information on expression, regulation, interaction, conserved elements, phenotype information. It also provides curated descriptions and cross-references to other life science databases, as well as identifying evolutionary relationship among identified factors.
prefix: planttfdb
pattern: ^[A-Z][a-z]{2}_([A-Za-z]{3}[0-9]{6})|([A-Za-z0-9\._\-#]*)$
prefixed: 0
resources:
 - identifier: MIR:00100772
   accessurl: http://planttfdb.cbi.pku.edu.cn/tf.php?uid=${id}
   test_id: Ath_AT1G01030.1
   description: PlantTFDB at Peking University
   homepage: http://planttfdb.cbi.pku.edu.cn
   institution: Center for Bioinformatics, Peking University, Beijing
   location: Peoples Republic of China
   official: false
---

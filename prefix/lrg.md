---
identifier: MIR:00000376
name: Locus Reference Genomic
description: Locus Reference Genomic (LRG) provides identifiers to stable genomic DNA sequences for regions of the human genome, providing a recognized reference-sequence standard for reporting sequence variants. LRG is maintained by the NCBI and the European Bioinformatics Institute (EBI).
prefix: lrg
pattern: ^LRG_\d+$
prefixed: 0
local_id: LRG_1
synonyms:
 - LRG
resources:
 - identifier: MIR:00100478
   accessurl: ftp://ftp.ebi.ac.uk/pub/databases/lrgex/${lid}.xml
   keyword: Osteogenesis Imperfecta
   description: Locus Reference Genomic at University of Leicester
   homepage: http://www.lrg-sequence.org/
   institution: Department of Genetics, University of Leicester, Leicester
   location: UK
   official: false
 - identifier: MIR:00100627
   accessurl: http://www.ensembl.org/Homo_sapiens/LRG/Summary?lrg=${lid}
   keyword: Chromosome 17: 50,182,096-50,206,639
   description: Locus Reference Genomic through Ensembl
   homepage: http://www.ensembl.org/
   institution: EnSembl, Sanger Institute and European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
 - identifier: MIR:00100629
   accessurl: http://asia.ensembl.org/Homo_sapiens/LRG/Summary?lrg=${lid}
   keyword: Chromosome 17: 50,182,096-50,206,639
   description: Locus Reference Genomic through Ensembl mirror (asia)
   homepage: http://asia.ensembl.org/
   institution: 
   location: Singapore
   official: false
 - identifier: MIR:00100630
   accessurl: http://uswest.ensembl.org/Homo_sapiens/LRG/Summary?lrg=${lid}
   keyword: Chromosome 17: 50,182,096-50,206,639
   description: Locus Reference Genomic through Ensembl mirror (US west)
   homepage: http://uswest.ensembl.org/
   institution: 
   location: USA
   official: false
 - identifier: MIR:00100631
   accessurl: http://useast.ensembl.org/Homo_sapiens/LRG/Summary?lrg=${lid}
   keyword: Chromosome 17: 50,182,096-50,206,639
   description: Locus Reference Genomic through Ensembl mirror (US east)
   homepage: http://useast.ensembl.org/
   institution: 
   location: USA
   official: false
---

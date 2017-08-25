---
identifier: MIR:00000003
name: Ensembl
description: Ensembl is a joint project between EMBL - EBI and the Sanger Institute  to develop a software system which produces and maintains automatic annotation on selected eukaryotic genomes. This collections also references outgroup organisms.
prefix: ensembl
pattern: ^((ENS[A-Z]*[FPTG]\d{11}(\.\d+)?)|(FB\w{2}\d{7})|(Y[A-Z]{2}\d{3}[a-zA-Z](\-[A-Z])?)|([A-Z_a-z0-9]+(\.)?(t)?(\d+)?([a-z])?))$
prefixed: 0
resources:
 - identifier: MIR:00100011
   accessurl: http://www.ensembl.org/id/${id}
   test_id: ENSG00000139618
   description: Ensembl at Sanger/EMBL-EBI
   homepage: http://www.ensembl.org/
   institution: Sanger Institute and European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100561
   accessurl: http://uswest.ensembl.org/id/${id}
   test_id: ENSG00000139618
   description: Ensembl US West mirror
   homepage: http://uswest.ensembl.org/
   institution: 
   location: USA
   official: false
 - identifier: MIR:00100562
   accessurl: http://useast.ensembl.org/id/${id}
   test_id: ENSG00000139618
   description: Ensembl US East mirror
   homepage: http://useast.ensembl.org/
   institution: 
   location: USA
   official: false
 - identifier: MIR:00100563
   accessurl: http://asia.ensembl.org/id/${id}
   test_id: ENSG00000139618
   description: Ensembl Asia mirror
   homepage: http://asia.ensembl.org/
   institution: 
   location: Singapore
   official: false
---

---
identifier: MIR:00000149
name: CryptoDB
description: CryptoDB is one of the databases that can be accessed through the EuPathDB (http://EuPathDB.org; formerly ApiDB) portal, covering eukaryotic pathogens of the genera Cryptosporidium, Giardia, Leishmania, Neospora, Plasmodium, Toxoplasma, Trichomonas and Trypanosoma. While each of these groups is supported by a taxon-specific database built upon the same infrastructure, the EuPathDB portal offers an entry point to all these resources, and the opportunity to leverage orthology for searches across genera.
prefix: cryptodb
pattern: ^\w+
prefixed: 0
resources:
 - identifier: MIR:00100194
   accessurl: http://cryptodb.org/cryptodb/showRecord.do?name=GeneRecordClasses.GeneRecordClass&source_id=${id}
   test_id: cgd7_230
   description: CryptoDB at EuPathDB
   homepage: http://cryptodb.org/cryptodb/
   institution: Center for Tropical & Emerging Global Diseases, University of Georgia
   location: USA
   official: false
---

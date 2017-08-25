---
identifier: MIR:00000150
name: PlasmoDB
description: AmoebaDB is one of the databases that can be accessed through the EuPathDB (http://EuPathDB.org; formerly ApiDB) portal, covering eukaryotic pathogens of the genera Cryptosporidium, Giardia, Leishmania, Neospora, Plasmodium, Toxoplasma, Trichomonas and Trypanosoma. While each of these groups is supported by a taxon-specific database built upon the same infrastructure, the EuPathDB portal offers an entry point to all these resources, and the opportunity to leverage orthology for searches across genera.
prefix: plasmodb
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100195
   accessurl: http://plasmodb.org/plasmo/showRecord.do?name=GeneRecordClasses.GeneRecordClass&source_id=${id}
   test_id: PF11_0344
   description: PlasmoDB at EuPathDB
   homepage: http://plasmodb.org/plasmo/
   institution: Center for Tropical & Emerging Global Diseases, University of Georgia
   location: USA
   official: false
---

---
identifier: MIR:00000465
name: YDPM
description: The YDPM database serves to support the Yeast Deletion and the Mitochondrial Proteomics Project. The project aims to increase the understanding of mitochondrial function and biogenesis in the context of the cell. In the Deletion Project, strains from the deletion collection were monitored under 9 different media conditions selected for the study of mitochondrial function. The YDPM database contains both the raw data and growth rates calculated for each strain in each media condition.
prefix: ydpm
pattern: ^Y[A-Z]{2}\d+[CW]$
prefixed: 0
resources:
 - identifier: MIR:00100600
   accessurl: http://www-deletion.stanford.edu/cgi-bin/YDPM/YDPM_search.cgi?thelist=${id}
   test_id: YAL001C
   description: YDPM at Stanford University School of Medicine
   homepage: http://www-deletion.stanford.edu/YDPM/
   institution: Stanford University School of Medicine, Stanford, California
   location: USA
   official: false
---

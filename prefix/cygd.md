---
identifier: MIR:00000262
name: CYGD
description: The MIPS Comprehensive Yeast Genome Database (CYGD) provides information on the molecular structure and functional network of the entirely sequenced the budding yeast, Saccharomyces cerevisiae, as well as on related yeasts which are used for comparative analysis.
prefix: cygd
pattern: ^\w{2,3}\d{2,4}(\w)?$
prefixed: 0
resources:
 - identifier: MIR:00100684
   accessurl: http://pedant.helmholtz-muenchen.de/pedant3htmlview/pedant3view?Db=p3_p13838_Sac_cerev&Method=ReportGene&GeneticelemCode=${id}
   test_id: YFL039c
   description: CYGD PEDANT Interface at Biomax Informatics
   homepage: http://pedant.helmholtz-muenchen.de/pedant3htmlview/pedant3view?Method=start_method&Db=p3_p13838_Sac_cerev
   institution: Biomax Informatics AG, Planegg
   location: Germany
   official: false
---

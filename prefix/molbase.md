---
identifier: MIR:00000458
name: Molbase
description: Molbase provides compound data information for researchers as well as listing suppliers and price information. It can be searched by keyword or CAS indetifier.
prefix: molbase
pattern: ^(\d{1,7}\-\d{2}\-\d)|([A-Za-z0-9\+\-\_]+)$
prefixed: 0
resources:
 - identifier: MIR:00100593
   accessurl: http://www.molbase.com/en/index.php?app=search&search_keyword=${id}
   test_id: 128796-39-4
   description: Molbase at Chinese Academy of Sciences
   homepage: http://www.molbase.com/
   institution: Chinese Academy of Sciences, Xuhui District  Shanghai
   location: China
   official: false
---

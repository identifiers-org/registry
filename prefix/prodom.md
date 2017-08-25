---
identifier: MIR:00000117
name: ProDom
description: ProDom is a database of protein domain families generated from the global comparison of all available protein sequences.
prefix: prodom
pattern: ^PD\d+$
prefixed: 0
resources:
 - identifier: MIR:00100150
   accessurl: http://prodom.prabi.fr/prodom/current/cgi-bin/request.pl?question=DBEN&query=${id}
   test_id: PD10000
   description: ProDom Protein Domain Database
   homepage: http://prodom.prabi.fr/prodom/current/html/home.php
   institution: Laboratoire des Interactions Plantes-Microorganismes, INRA/CNRS
   location: France
   official: false
---

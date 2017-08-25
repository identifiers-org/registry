---
identifier: MIR:00000086
name: SABIO-RK Kinetic Record
description: SABIO-RK is a relational database system that contains information about biochemical reactions, their kinetic equations with their parameters, and the experimental conditions under which these parameters were measured. The kinetic record data set provides information regarding the kinetic law, measurement conditions, parameter details and other reference information.
prefix: sabiork.kineticrecord
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100117
   accessurl: http://sabiork.h-its.org/kineticLawEntry.jsp?viewData=true&kinlawid=${id}
   test_id: 5046
   description: SABIO-RK Reaction Kinetics Database - Kinetic Dataset
   homepage: http://sabiork.h-its.org/
   institution: Heidelberg Institute for Theoretical Studies  (HITS gGmbH)
   location: Germany
   official: false
---

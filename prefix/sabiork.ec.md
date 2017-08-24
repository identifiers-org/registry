---
identifier: MIR:00000128
name: SABIO-RK EC Record
description: SABIO-RK is a relational database system that contains information about biochemical reactions, their kinetic equations with their parameters, and the experimental conditions under which these parameters were measured. The EC record provides for a given enzyme classification (EC) the associated list of enzyme-catalysed reactions and their corresponding kinetic data.
prefix: sabiork.ec
pattern: ^((\d+)|(\d+\.\d+)|(\d+\.\d+\.\d+)|(\d+\.\d+\.\d+\.\d+))$
prefixed: 0
resources:
 - identifier: MIR:00100163
   accessurl: http://sabiork.h-its.org/newSearch?q=ecnumber:
   description: SABIO-RK Reaction Kinetics Database - Enzyme Classification (EC)
   location: Germany
   official: false
---

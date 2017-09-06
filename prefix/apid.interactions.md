---
identifier: MIR:00000576
name: APID Interactomes
description: APID (Agile Protein Interactomes DataServer) provides information on the protein interactomes of numerous  organisms, based on the integration of known experimentally validated protein-protein physical interactions (PPIs). Interactome data includes a report on  quality levels and coverage over the proteomes for each organism included. APID integrates PPIs from primary databases of molecular interactions (BIND, BioGRID, DIP, HPRD, IntAct, MINT) and also from experimentally resolved 3D structures (PDB) where more than two distinct proteins have been identified. This collection references protein interactors, through a UniProt identifier.
prefix: apid.interactions
pattern: ^([A-N,R-Z][0-9]([A-Z][A-Z, 0-9][A-Z, 0-9][0-9]){1,2})|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9])(\.\d+)?$
prefixed: 0
local_id: P01116
synonyms:
 - Agile Protein Interactomes DataServer
resources:
 - identifier: MIR:00100769
   accessurl: http://cicblade.dep.usal.es:8080/APID/Interactions.action?protein=${lid}
   keyword: IntAct
   description: APID at Salamanca
   homepage: http://cicblade.dep.usal.es:8080/APID/
   institution: Cancer Research Center (CiC-IBMCC), Consejo Superior de Investigaciones Científicas (CSIC) and Universidad de Salamanca (USAL), Salamanca
   location: Spain
   official: false
---

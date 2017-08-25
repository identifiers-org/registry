---
identifier: MIR:00000426
name: Golm Metabolome Database Analyte
description: Golm Metabolome Database (GMD) provides public access to custom mass spectral libraries, metabolite profiling experiments as well as additional information and tools. For GC-MS profiling analyses, polar metabolite extracts are chemically converted, i.e. derivatised into less polar and volatile compounds, so called analytes.  This collection references analytes.
prefix: gmd.analyte
pattern: ^([0-9a-fA-F]){8}(-([0-9a-fA-F]){4}){3}-([0-9a-fA-F]){12}$
prefixed: 0
resources:
 - identifier: MIR:00100549
   accessurl: http://gmd.mpimp-golm.mpg.de/Analytes/${id}
   test_id: 4f0fa9b6-514f-4ff4-98cc-0009bc08eb80
   description: Golm Metabolome Database (Analyte) at Max Planck Institute of Molecular Plant Physiology
   homepage: http://gmd.mpimp-golm.mpg.de/
   institution: Max Planck Institute of Molecular Plant Physiology, Potsdam
   location: Germany
   official: false
---

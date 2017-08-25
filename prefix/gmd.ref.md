---
identifier: MIR:00000425
name: Golm Metabolome Database Reference Substance
description: Golm Metabolome Database (GMD) provides public access to custom mass spectral libraries, metabolite profiling experiments as well as additional information and tools. Since metabolites often cannot be obtained in their respective native biological state, for example organic acids may be only acquirable as salts, the concept of reference substance was introduced. This collection references reference substances.
prefix: gmd.ref
pattern: ^([0-9a-fA-F]){8}(-([0-9a-fA-F]){4}){3}-([0-9a-fA-F]){12}$
prefixed: 0
resources:
 - identifier: MIR:00100548
   accessurl: http://gmd.mpimp-golm.mpg.de/ReferenceSubstances/${id}
   test_id: 8cf84adb-b4db-4807-ac98-0004247c35df
   description: Golm Metabolome Database (Reference Substance) at Max Planck Institute of Molecular Plant Physiology
   homepage: http://gmd.mpimp-golm.mpg.de/
   institution: Max Planck Institute of Molecular Plant Physiology, Potsdam
   location: Germany
   official: false
---

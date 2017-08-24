---
identifier: MIR:00000582
name: MultiCellDS collection
description: MultiCellDS is data standard for multicellular simulation, experimental, and clinical data. A collection groups one or more individual uniquely identified cell lines, snapshots, or collections. Primary uses are times series (collections of snapshots), patient cohorts (collections of cell lines), and studies (collections of time series collections).
prefix: multicellds.collection
pattern: ^MCDS_C_[a-zA-Z0-9]{1,10}$
prefixed: 0
resources:
 - identifier: MIR:00100779
   accessurl: http://multicellds.org/MultiCellDB/
   description: MultiCellDScollection at Keck School of Medicine
   location: USA
   official: false
---

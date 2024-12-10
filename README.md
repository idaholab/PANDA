# Authors

- **Michael Wu**  
  Contact: [michael.wu@inl.gov](mailto:michael.wu@inl.gov)

- **Jeremy Sharapov**  
  Contact: [jeremy.sharapov@inl.gov](mailto:jeremy.sharapov@inl.gov)

- **Matthew W. Anderson**  
  Contact: [matthew.anderson2@inl.gov](mailto:matthew.anderson2@inl.gov)

## PANDA: Predictive Automation of Novel Defect Anomalies

The quantitative analysis of dislocation-type defects in irradiated materials is critical to materials characterization in the nuclear energy industry. The conventional approach of an instrument scientist manually identifying any dislocation defects is both time-consuming and subjective, thereby potentially introducing inconsistencies in the quantification.

This work approaches dislocation-type defect identification and segmentation using a standard open source computer vision model, YOLOv11, that leverages topic-adjacent transfer learning to create a highly effective dislocation defect quantification tool while using only a minimal number of annotated micrographs for training. This model demonstrates the ability to segment both dislocation lines and loops concurrently in micrographs with high pixel noise levels and on two alloys not represented in the training set.

Inference of dislocation defects using transmission electron microscopy on three different irradiated alloys relevant to the nuclear energy industry are examined in this work with widely varying pixel noise levels and with completely unrelated composition and dislocation formations for practical post irradiation examination analysis.

## License

Copyright 2024, Battelle Energy Alliance, LLC, ALL RIGHTS RESERVED

This program ("Program") utilizes YOLOv11 under the [GNU Affero General Public License v3.0 (AGPL-3.0)](https://www.gnu.org/licenses/agpl-3.0.en.html#license-text). For more information about YOLOv11, see the [official documentation](https://docs.ultralytics.com/models/yolo11/).

You should have received a copy of the GNU AGPL-3.0 license along with this Program. If not, you may find a copy of it at [https://www.gnu.org/licenses/agpl-3.0.en.html#license-text](https://www.gnu.org/licenses/agpl-3.0.en.html#license-text).

The YOLOv11 is free software. You can redistribute it and/or modify it under the terms of GNU AGPL-3.0 as published by the Free Software Foundation, either version 3 of the License or (at your option) any later version.

The portion of the Program that is not YOLOv11 is owned by Battelle Energy Alliance (BEA) (Copyright 2024 BEA). The source code or instruction sets for running this portion of the program, along with the source code for YOLOv11, are made available to the user upon running the Program. This Program (including the YOLOv11 portion and the BEA portion) is licensed to the user under AGPL-3.0 and can be used according to that license for so long as the user is in compliance with that license.

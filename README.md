# OMBRIA

This repo contains the OMBRIA dataset as described in the journal "OmbriaNet—Supervised Flood Mapping via Convolutional Neural Networks Using Multitemporal Sentinel-1 and Sentinel-2 Data Fusion" (https://ieeexplore.ieee.org/abstract/document/9723593). 

It is a  Sentinel-1 and Sentinel-2 imagery dataset constructed for benchmarking the OmbriaNet deep learning CNN architecture. OmbriaNet
was designed for adressing the flood mapping problem.
Each satellite module contains three folders:
1. The folder named BEFORE contains image of a region taken before a selected flood event
2. The folder named AFTER contains image of the same region taken after the flood event
3. The folder named MASK contains a binary ground truth image of the region as produced by the EMS Rapid mapping.

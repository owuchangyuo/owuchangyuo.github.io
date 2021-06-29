---
title: "Skeleton-Aware Network for Aircraft Landmark Detection"
collection: publications
permalink: /publications/SALD
---  
[[PDF]](https://owuchangyuo.github.io/files/SALD.pdf) 

## Abstract
The landmark detection has been widely investigated for the human pose with rapid progress in recent years. In this work, we aim at dealing with a new problem: aircraft landmark detection in the wild. We have a key observation: the aircraft is a rigid object with global structural relationships between local landmarks. This motivates us to progressively learn the global geometrical structure and local landmark localization in a coarse-to-fine guidance manner. In this paper, we propose a simple yet effective skeleton-aware landmark detection (SALD) network, including one stream for exploiting the coarse global skeleton structure and one stream for the precise local landmarks localization. The global skeleton structure models the aircraft images" into skeleton lines, in which the multiple skeletons of the holistic aircraft and the parts are explicitly extracted to serve as the geometrical structure constraints for landmarks. Then, the local landmark localization precisely detects the key points with the guidance of skeleton lines. Consequently, the progressive strategy of extracting lines from images, detecting points with lines significantly eases the landmark detection task by decomposing the task into the simpler coarse-to-fine sub-tasks, thus further improving the detection performance. Extensive experimental results show the superiority of proposed method compared to state-of-the-arts.

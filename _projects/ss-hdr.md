---
title: "Self-supervised HDR Imaging from Motion and Exposure Cues"
collection: projects
permalink: /project/ss-hdr
image: /assets/images/SS_HDR_teaser.png
date: 2021-08-01
# venue: 'Automation. Advances in Intelligent Systems and Computing'
# paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-13273-6_43'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
# citation: 'Michal Nazarczuk, Maciej Cader, Michal Kowalik and Mikolaj Jankowski. &quot;Proposition of the Methodology of the Robotised Part Replication Implemented in Industry 4.0 Paradigm.&quot, In <i>Automation 2019. Advances in Intelligent Systems and Computing</i>, (920), 2019.'
citation: 'Michal Nazarczuk, Sibi Catley-Chandar, Ales Leonardis, Eduardo Pérez-Pellitero'
---

**[[Paper]](https://arxiv.org/abs/2203.12311)**

<div class="archive__item-image-full">
  <img src="/assets/images/SS_HDR_main.png" alt="">
</div>

## Abstract

Recent High Dynamic Range (HDR) techniques extend the capabilities of current cameras where scenes with a wide range of illumination can not be accurately captured with a single low-dynamic-range (LDR) image. This is generally accomplished by capturing several LDR images with varying exposure values whose information is then incorporated into a merged HDR image. While such approaches work well for static scenes, dynamic scenes pose several challenges, mostly related to the difficulty of finding reliable pixel correspondences. Data-driven approaches tackle the problem by learning an end-to-end mapping with paired LDR-HDR training data, but in practice generating such HDR ground-truth labels for dynamic scenes is time-consuming and requires complex procedures that assume control of certain dynamic elements of the scene (e.g. actor pose) and repeatable lighting conditions (stop-motion capturing). In this work, we propose a novel self-supervised approach for learnable HDR estimation that alleviates the need for HDR ground-truth labels. We propose to leverage the internal statistics of LDR images to create HDR pseudo-labels. We separately exploit static and well-exposed parts of the input images, which in conjunction with synthetic illumination clipping and motion augmentation provide high quality training examples. Experimental results show that the HDR models trained using our proposed self-supervision approach achieve performance competitive with those trained under full supervision, and are to a large extent superior to previous methods that equally do not require any supervision. 

<!-- ## Citation

```
@article{nazarczuk2019,
  title={Proposition of the Methodology of the Robotised Part Replication Implemented in Industry 4.0 Paradigm},
  author={Nazarczuk, Michal and Cader, Maciej and Kowalik, Michal and Jankowski, Mikolaj},
  journal={Automation 2019. Advances in Intelligent Systems and Computing},
  volume={920},
  year={2019}
  }
``` -->


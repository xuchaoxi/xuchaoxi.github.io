---
title: "Fully Deep Learning for Slit-lamp Photo based Nuclear Cataract Grading"
collection: publications
permalink: /publication/2019-10-13-miccai19-cataract
date: 2019-10-13
venue: 'International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)'
paperurl: '/files/miccai2019-cataract.pdf'
authors: '<b>Chaoxi Xu</b>, Xiangjia Zhu, Wenwen He, Yi Lu, Xixi He, Zongjiang Shang, Jun Wu, Keke Zhang, Yinglei Zhang, Xianfang Rong, Zhennan Zhao, Lei Cai, Dayong Ding and Xirong Li (2019)'
---
Age-related cataract is a priority eye disease, with nuclear cataract as its most common type. This paper aims for automated nuclear cataract grading based on slit-lamp photos. Different from previous efforts which rely on traditional feature extraction and grade modeling techniques, we propose in this paper a fully deep learning based solution. Given a slit-lamp photo, we localize its nuclear region by Faster R-CNN, followed by a ResNet-101 based grading model. In order to alleviate the issue of imbalanced data, a simple batch balancing strategy is introduced for improving the training of the grading network. Tested on a clinical dataset of 157 slit-lamp photos from 39 female and 31 male patients, the proposed solution outperforms the state-of-the-art, reducing the mean absolute error from 0.357 to 0.313. In addition, our solution processes a slit-lamp photo in approximately 0.1 second, which is two order faster than the state-of-the-art. With its effectiveness and efficiency, the new solution is promising for automated nuclear cataract grading.

[Download paper here](/files/miccai2019-cataract.pdf)

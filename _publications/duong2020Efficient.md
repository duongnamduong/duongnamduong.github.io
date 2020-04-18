---
title: "Efficient multi-output scene coordinate prediction for fast and accurate camera relocalization from a single RGB image"
collection: publications
permalink: /publication/duong2020Efficient
date: 2020-01-07 01:00:00 +0100
venue: 'Computer Vision and Image Understanding'
pubtype: 'journal'
authors: 'Nam-Duong Duong, Catherine Soladie, Amine Kacete, Pierre-Yves Richard, Jérôme Royan'
excerpt_separator: ""
---
Camera relocalization refers to the problematic of the camera pose estimation including 3D translation and 3D rotation expressed in the world coordinate system with no temporal constraint. Camera relocalization is necessary in localization systems. However, it is still challenging to have both a real-time and accurate method. In this paper, we introduce our data-oriented hybrid method merging both machine learning and geometric approaches for fast and accurate camera relocalization from a single RGB image. We propose an efficient multi-output deep-forest regression based on a sparse feature detection, that uses a whole learned feature vector at each split function to improve the accuracy of 2D–3D point correspondences. Especially, multiple coordinate regression of our deep-forest allows to deal with ambiguous repetitive structure. The learned feature extraction is able to be pre-trained and reused for different scenes. The use of sparse feature detection reduces processing time and increases accuracy of predictions. Finally, we show favorable results in terms of accuracy and computational time compared to the state-of-the-art methods.
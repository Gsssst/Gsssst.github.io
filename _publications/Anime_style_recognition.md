---
title: "A challenging benchmark of Anime Style Recognition"
collection: publications
permalink: /publication/Anime_style_recognition
excerpt: 'This paper is about the Anime style recognition.'
date: 2022-06-19
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops'
paperurl: 'http://Gsssst.github.io/files/paper.pdf'
citation: 'H. Li , S. Guo et al., "A Challenging Benchmark of Anime Style Recognition," 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), New Orleans, LA, USA, 2022, pp. 4720-4729'
---

Given two images of different anime roles, anime style recognition (ASR) aims to learn abstract painting style to determine whether the two images are from the same work, which is an interesting but challenging problem. Unlike biometric recognition, such as face recognition, iris recognition, and person re-identification, ASR suffers from a much larger semantic gap but receives less attention. In this paper, we propose a challenging ASR benchmark. Firstly, we collect a large-scale ASR dataset (LSASRD), which contains 20,937 images of 190 anime works and each work at least has ten different roles. In addition to the large-scale, LSASRD contains a list of challenging factors, such as complex illuminations, various poses, theatrical colors and exaggerated compositions. Secondly, we design a cross-role protocol to evaluate ASR performance, in which query and gallery images must come from different roles to validate an ASR model is to learn abstract painting style rather than learn discriminative features of roles. Finally, we apply two powerful person re-identification methods, namely, AGW and TransReID, to construct the baseline performance on LSASRD. Surprisingly, the recent transformer model (i.e., TransReID) only acquires a 42.24% mAP on LSASRD. Therefore, we believe that the ASR task of a huge semantic gap deserves deep and long-term research.

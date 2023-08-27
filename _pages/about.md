---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a BSc student in RIT's [Neural Adaptive Computing Laboratory](https://www.cs.rit.edu/~ago/nac_lab.html) working with [Dr. Alexander Ororbia II](https://www.cs.rit.edu/~ago/) to develop spiking neural network models of human-level decision making. I am concurrently working with [Dr. Josh McDermott](https://web.mit.edu/jhm/www/) as a visiting student in MIT's [Laboratory for Computational Audition](http://mcdermottlab.mit.edu/index.html). There, I am focused on developing more biologically plausible models of human hearing.

Current research
======
My work aims to bridge artificial intelligence and the biological brain and to someday enable the digital reconstruction of the human brain. My current research uses neural networks and tries to incorporate biologically plausible mechanisms within them to more closely match the neural properties found in the brain.

R-STDP for spiking neural networks trained to perform sound localization
------
[Project description]

Modeling divisive normalization in the central auditory pathway with convolutional neural networks
------
Divisive normalization has been widely proposed to contribute to efficient neural representations of auditory information, which enhances perceptual contrast and reduces statistical dependencies in auditory input. These mechanisms, while critical to many auditory tasks we perform on a daily basis, are compromised in people with hearing impairments. To gain a clearer understanding of how these mechanisms work computationally and their importance for task optimization, we create convolutional neural network (CNN) models of the central auditory pathway, incorporating divisive normalization at each level. The weights and span of the local divisive neighborhood are optimized through gradient descent, with the model trained to perform word recognition and sound localization. Our results suggest that the learned neighborhoods reproduce key properties of biological normalization such as adaptation to ongoing stimuli. Furthermore, the model is shown to exhibit human-level performance with improved generalizability to out-of-distribution inputs. Our future work aims to investigate whether the suppressive effects found in biology can also be reproduced and whether these types of models can be applied in to study of hearing impaired humans.


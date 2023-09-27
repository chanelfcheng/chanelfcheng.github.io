---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a BSc student at RIT studying Computer Science. I am concurrently working with [Dr. Josh McDermott](https://web.mit.edu/jhm/www/) as a visiting student in MIT's [Laboratory for Computational Audition](http://mcdermottlab.mit.edu/index.html). There, I am focused on developing more biologically plausible models of human hearing.

Current research
======
My research broadly aims to bridge artificial intelligence and the biological brain
with the ultimate goal of reconstructing brain functionality and human behavior.
My current research trains neural networks to perform auditory tasks and
incorporates biologically plausible mechanisms within them to more closely match
the neural properties found in the brain.

Divisive normalization in the central auditory pathway
------
Divisive normalization has been widely proposed as a canonical neural computation contributing to efficient representations of auditory information. It has been shown to enhance local perceptual contrast and reduce statistical dependencies in auditory input. However, it is not known whether such mechanisms arise as a consequence of evolution to efficiently perform auditory tasks. In this study, we created convolutional neural network models of the central auditory pathway, incorporating local divisive normalization in the frequency and time domains. The weights and span of the normalization kernels were optimized through gradient descent, with the model trained to perform word recognition. Network activations were then analyzed to probe for signatures of adaptation to ongoing stimuli and two-tone suppression observed in neurophysiological experiments. We show that the trained model exhibits word recognition performance and generalizability to unseen input distributions on par with that of humans. We further show that the learned kernels reproduced effects of adaptation observed in auditory neurons. This work provides novel insights for whether divisive normalization properties might emerge from task optimization. Our next steps aim to investigate whether the suppressive effects found in biology can also be reproduced and whether these types of models can be applied in the study of hearing impaired humans.


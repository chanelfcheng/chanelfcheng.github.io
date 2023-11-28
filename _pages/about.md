---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a BSc student at RIT studying Computer Science, currently working with [Dr. Josh McDermott](https://web.mit.edu/jhm/www/) as a visiting student in MIT's [Laboratory for Computational Audition](http://mcdermottlab.mit.edu/index.html). There, I am focused on developing more biologically plausible models of human hearing.

Current research
======
My research broadly aims to bridge artificial intelligence and the biological brain
with the ultimate goal of reconstructing brain functionality and human behavior.
My current research trains neural networks to perform auditory tasks and
incorporates biologically plausible mechanisms within them to more closely match
the neural properties found in the brain.

Divisive normalization in the auditory system
------
Divisive normalization (DN) is a canonical neural computation that adjusts neuron
responses based on the local responses of surrounding neurons and
contributes to efficient representations of information in the auditory system.
However, it is not known whether such mechanisms arise as a result of evolution
to perform auditory tasks or as a result of optimizing for statistical
independence in stimuli.
To study this phenomena, we created convolutional neural network (CNN) models of
the auditory system, with DN applied after each convolution, and
represented sounds using cochleagrams from a cochlea model.
Following optimization to perform an auditory task, we probed network
activations for signatures of two nonlinear phenomena observed in
the biological auditory system: adaptation to ongoing stimuli and two-tone
suppression. 
Results show that after optimization, DN applied instantaneously across time and
frequency yielded response patterns that were most biologically consistent,
suggesting a potential interplay between the development of normalization and
optimization for natural auditory tasks. Additionally, generalization to
out-of-distribution stimuli was improved, providing a parallel to how humans
generalize to new sounds they haven't learned before. Our next steps aim
to investigate whether these types of models can be applied in the study of
hearing impairment.


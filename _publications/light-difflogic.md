---
title: "Light differentiable logic gate networks"
collection: publications
category: underreview
permalink: /publication/light-difflogic
excerpt: 'Reparametrizing DLGNs.'
date: 2025-09-25
venue: 'Under review'
slidesurl: 'http://lukas-ruettgers.github.io/files/light-difflogic.pdf'
paperurl: 'http://lukas-ruettgers.github.io/files/light-difflogic.pdf'
bibtexurl: 'http://lukas-ruettgers.github.io/files/light-difflogic.bib'
citation: 'Lukas Rüttgers, Till Aczel, Andreas Plesner, Roger Wattenhofer. (2025). &quot;Light Differentiable Logic Gate Networks.&quot; <i>Under review</i>. 1(1).'
---
Differentiable logic gate networks (DLGNs) exhibit extraordinary efficiency at inference while sustaining competitive accuracy.
But vanishing gradients, discretization errors, and high training cost impede scaling these networks.
Even with dedicated parameter initialization schemes from subsequent works, increasing depth still harms accuracy.
We show that the root cause of these issues lies in the underlying parametrization of logic gate neurons themselves.
To overcome this issue, we propose a reparametrization that also shrinks the parameter size logarithmically in the number of inputs per gate.
For binary inputs, this already reduces the model size by 4x, speeds up the backward pass by up to 1.86x, and converges in 8.5x fewer training steps.
On top of that, we show that the accuracy on CIFAR-100 remains stable and sometimes superior to the original parametrization.

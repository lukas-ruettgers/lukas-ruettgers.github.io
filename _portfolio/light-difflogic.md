---
title: "Light differentiable logic gate networks"
excerpt: 'Reparametrizing differentiable logic gate networks to make them more lightweight and scalable.<br/><img src="/images/light-difflogic.png">'
collection: portfolio
---

![Illustration of reparametrization](/images/light-difflogic.png)

# Abstract
Differentiable logic gate networks (DLGNs) exhibit extraordinary efficiency at inference while sustaining competitive accuracy.
But vanishing gradients, discretization errors, and high training cost impede scaling these networks.
With our reparametrization, we tackle these shortcoming and make DLGNs more scalable in depth and complexity. 
The implementation of our reparametrization is available at [GitHub](https://github.com/lukas-ruettgers/difflogic-iwp).

# Presentation (Manim)
Use arrow keys to navigate through slides and press `F` for full screen.<br/>
You can also directly open the presentation [here](/files/light-difflogic-pres.html).<br/>
<div style="position:relative;padding-bottom:56.25%;">
    <!-- 56.25 comes from aspect ratio of 16:9, change this accordingly -->
    <iframe
        style="width:100%;height:100%;position:absolute;left:0px;top:0px;"
        frameborder="0"
        width="100%"
        height="100%"
        allowfullscreen
        allow="autoplay"
        src="/files/light-difflogic-pres.html">
    </iframe>
</div><br/>

# Paper
<embed src="/files/light-difflogic.pdf" width="500" height="375" 
 type="application/pdf">
---
title: "Cosmic Velocity Field Reconstruction Using AI"
collection: publications
permalink: /publication/arxiv-2105-09450
excerpt: 'This paper is about reconstructing cosmological large-scale structure velocity field by deep learning.'
date: 2021-05-18
venue: 'Astrophysical Journal'
paperurl: 'https://arxiv.org/pdf/2105.09450'
citation: 'Ziyong Wu, <b>Zhenyu Zhang</b>, Shuyang Pan et al., <i>Astrophys. J.</i>, 913 (2021) 1, 2'
---

<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

Abstract
--------------

We develop a deep-learning technique to infer the nonlinear velocity field from the dark matter density field. The deep-learning architecture we use is a “U-net” style convolutional neural network, which consists of 15 convolution layers and 2 deconvolution layers. This setup maps the three-dimensional density field of $32^3$ voxels to the three-dimensional velocity or momentum fields of $20^3$ voxels. Through the analysis of the dark matter simulation with a resolution of $2h^{−1} Mpc$, we find that the network can predict the the nonlinearity, complexity, and vorticity of the velocity and momentum fields, as well as the power spectra of their value, divergence, and vorticity and its prediction accuracy reaches the range of $k \simeq 1.4 h Mpc^{−1}$ with a relative error ranging from $1\%$ to $\lesssim 10\%$. A simple comparison shows that neural networks may have an overwhelming advantage over perturbation theory in the reconstruction of velocity or momentum fields.

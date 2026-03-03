---
title: "SketchFeature: High-Quality Per-Flow Feature Extractor Towards Security-Aware Data Plane"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about a famous math equation, $$E=mc^2$$'
date: 2025-05-1
venue: 'Network and Distributed System Security (NDSS) Symposium'
#paperurl: 'https://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'

venue_short: 'NDSS' 
paperurl: 'https://www.ndss-symposium.org/ndss-paper/sketchfeature-high-quality-per-flow-feature-extractor-towards-security-aware-data-plane/'
authors: 'Sian Kim, <b>Seyed Mohammad Mehdi Mirnajafizadeh</b>, Bara Kim, Rhongho Jang, DaeHun Nyang'
abstract: 'Intelligent Network Data Plane (INDP) is emerging as a promising direction for in-network security due to the advancement of machine learning technologies and the importance of fast mitigation of attacks. However, the feature extraction function still poses various challenges due to the multiple hardware constraints in the network data plane, especially for the advanced per-flow 3rd-order features (e.g., inter-packet delay and packet size distributions) preferred by recent security applications. In this paper, we discover novel attack surfaces of state-of-the-art data plane feature extractors that had to accommodate the hardware constraints, allowing adversaries to evade the entire attack detection loop of the in-network intrusion detection systems. To eliminate the attack surfaces fundamentally, we pursue an evolution of a probabilistic (sketch) approach to enable flawless 3rd-order feature extraction at the data plane, highlighting High-resolution, All-flow, and Full-range (HAF) 3rd-order feature measurement capacity. To our best knowledge, the proposed scheme, namely SketchFeature, is the first sketch-based feature extractor fully deployable in the data plane. Through extensive analyses, we confirmed the robust performance of the proposed feature extractor theoretically and experimentally. Furthermore, we ran two security use cases, namely covert channel and DDoS detections, with SketchFeature as the feature extractor, and achieved near-optimal attack detection performance with machine learning.'
bibtex: '@inproceedings{Kim2025SketchFeature, author = {Sian Kim and Seyed Mohammad Mehdi Mirnajafizadeh and Bara Kim and Rhongho Jang and DaeHun Nyang}, title = {SketchFeature: High-Quality Per-Flow Feature Extractor Towards Security-Aware Data Plane}, booktitle = {Proc. of ISOC {NDSS}}, year = {2025} }'




header:
    teaser: "SKF.png"
teaser_fit: true
---

Using [MathJax](https://www.mathjax.org/) in the description is supported - $$E=mc^2$$ - however, the use must be mindful that the default delimiters are `$$...$$` and `\\[...\\]` which differs from the `$...$` that is typically expected.

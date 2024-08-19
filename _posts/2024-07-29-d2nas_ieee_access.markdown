---
layout: post
title:  "D2NAS: Efficient Neural Architecture Search with Performance Improvement and Model Size Reduction for Diverse Tasks"
date:   2024-07-29 22:21:59 +00:00
image: images/d2nas.png
categories: research
author: "Suengyub Han"
authors: "Jungeun Lee, <strong>Seungyub Han</strong>, Jungwoo Lee"
venue: "IEEE Access"
paper: https://ieeexplore.ieee.org/abstract/document/10613774
slides: 
code: 
---
We introduce D2NAS, Differential and Diverse NAS, leveraging techniques such as Differentiable ARchiTecture Search (DARTS) and Diverse-task Architecture SearcH (DASH) for architecture discovery. When we evaluated on NAS-Bench-360 tasks, which includes 10 numbers of diverse tasks for 1D, 2D, 2D Dense (tightly interconnected data) tasks, D2NAS reduces average error rates by 12.2%, while achieving an 85.1% reduction in average parameters (up to 97.3%) and a 91.3% reduction in Floating Point Operations (FLOPs, up to 99.3%) compared to DASH.
---
title: "UniTex: Single-chart texture reconstruction from multi-view images"
collection: publications
category: manuscripts
permalink: /publication/unitex
excerpt: 'UniTex reconstructs high‑fidelity single‑chart textures from multi‑view images using color‑aware cut generation, diffusion‑based novel views, and differentiable rendering.'
date: 2026-04-21
venue: 'June'
paperurl: 'http://ryan0399.github.io/files/1-s2.0-S0097849326000701-main.pdf'
citation: 'Husen Li, Dong Xiao, Jinghao Zhang, Renjie Chen. UniTex: Single-chart texture reconstruction from multi-view images. <i>Computers & Graphics</i>, vol. 137, 2026, article 104599. ISSN 0097-8493. https://doi.org/10.1016/j.cag.2026.104599'
---

Reconstructing textures from multi-view images is a fundamental task in computer graphics and computer vision, supporting applications such as virtual production, digital heritage preservation, and content creation. However, existing methods often produce fragmented UV atlases with misaligned seams, which limit their utility in downstream workflows. We present UniTex, a novel framework for reconstructing high-fidelity, single-chart textures from multi-view images. To ensure texture completeness and usability, we introduce a color-aware cut generation algorithm that strategically avoids cuts through salient texture regions, ensuring a seamless, artist-friendly atlas. To improve texture coverage and recover missing details in under-captured regions, we leverage diffusion priors to synthesize novel viewpoints, which provide additional supervision for texture reconstruction. Finally, we employ a physically based differentiable rendering framework that alternately optimizes material and illumination parameters, achieving realistic decoupling of lighting from textures. Extensive experiments demonstrate that UniTex outperforms state-of-the-art methods in visual fidelity, atlas integrity, and practical usability—enabling direct integration into 3D workflows without manual stitching.

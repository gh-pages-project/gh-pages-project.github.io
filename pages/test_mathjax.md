---
layout: page
title: Test MathJax
description: test how to use MathJax
author: author_name
date: 18-11-2024
---


We can include inline math: $x e^{x+1}$,

and a math block:

$$E^2 = c^2 \mathbf{p}\cdot \mathbf{p} + \left(m_0 c^2\right)^2$$

<!-- MathJax -->
<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

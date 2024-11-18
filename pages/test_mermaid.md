---
layout: page
title: Including diagrams
description: Include diagrams using Mermaid
use_mermaid: true
author: {{site.author}}
date: 18-11-2024
---

Uses [Mermaid](https://mermaid.js.org/)
Flow chart:

<pre class="mermaid">
graph TD
    A[T1] --> B(T2)
    B --> C{T3}
    C --> D[T4]
    C --> E[T5]
    E --> B
    D --> F[T6]
    F --> B
</pre>	

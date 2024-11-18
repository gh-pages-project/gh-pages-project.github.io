---
layout: page
title: A page with comments enabled
description: test giscus comments
giscus_comments: true
author: author_name
date: 17-11-2024
---

Here is a simple flow chart:

<pre class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</pre>	

<script type="module">
	import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
	mermaid.initialize({
		startOnLoad: true,
		theme: 'dark'
	});
</script>

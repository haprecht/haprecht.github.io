---
layout: default
---

## Welcome to another page

_yay_

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

<pre>
  <code class="language-mermaid">graph LR
    A--&gt;B
  </code>
</pre>

<div class="mermaid">graph LR
A--&gt;B
</div>

<script>
var config = {
    startOnLoad:true,
    theme: 'forest',
    flowchart:{
            useMaxWidth:false,
            htmlLabels:true
        }
};
mermaid.initialize(config);
window.merm


[back](./)

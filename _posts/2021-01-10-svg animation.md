---
layout: page
title:  “咔嚓”相机
excerpt_separator: "<!--more-->"
categories:
     - SVG制作
tags:
  - svg
---

### 跟我一起领略相机的神奇！（位移加旋转）

<!--more-->

<section>
<svg width="500" height="350" xmlns="http://www.w3.org/2000/svg">
  <g> 
    <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="camera-retro" class="svg-inline--fa fa-camera-retro fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 1200"><path fill="currentColor" d="M48 32C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h416c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48H48zm0 32h106c3.3 0 6 2.7 6 6v20c0 3.3-2.7 6-6 6H38c-3.3 0-6-2.7-6-6V80c0-8.8 7.2-16 16-16zm426 96H38c-3.3 0-6-2.7-6-6v-36c0-3.3 2.7-6 6-6h138l30.2-45.3c1.1-1.7 3-2.7 5-2.7H464c8.8 0 16 7.2 16 16v74c0 3.3-2.7 6-6 6zM256 424c-66.2 0-120-53.8-120-120s53.8-120 120-120 120 53.8 120 120-53.8 120-120 120zm0-208c-48.5 0-88 39.5-88 88s39.5 88 88 88 88-39.5 88-88-39.5-88-88-88zm-48 104c-8.8 0-16-7.2-16-16 0-35.3 28.7-64 64-64 8.8 0 16 7.2 16 16s-7.2 16-16 16c-17.6 0-32 14.4-32 32 0 8.8-7.2 16-16 16z"></path></svg>
    <animateTransform attributeName="transform" begin="0s" dur="10s" type="rotate" from="0 160 160" to="360 160 160" repeatCount="indefinite"/>
    <animate attributeName="transform"  
           to="100"
           dur="3s"
           begin="0s" type="rotate" from="0 160 160" to="360 160 160" repeatCount="indefinite"/>
  </g>
</svg>
 </section>
  
  **别眨眼，让我们一起看看代码是怎样的**
```
<animateTransform attributeName="transform" begin="0s" dur="10s" type="rotate" from="0 160 160" to="360 160 160" repeatCount="indefinite"/>
```

---
layout: default
title:  Khiti & Serah Matoya
permalink: /khiti
---
<div class="outer-cols">
<div id="left" class="column">
    <div class="top-left"></div>
    <div class="bottom">
    <img id="khiti-img" src="assets/img/khiti_1.jpg">
    </div>
</div>
<div id="right" class="column">
    <div class="top-right">
        <h1>Khiti and Serah Matoya</h1>
    </div>
    <div class="bottom">
        {% capture my_include %}{% include khiticontent.md %}{% endcapture %}
        {{ my_include | markdownify }}
    </div>
</div>
</div>
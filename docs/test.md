---
layout: Page
title: テスト
permalink: /test/
---
<script src='p5.js'></script>
<div id='container'></div>
<script>
let sketch = function(p) {
p.setup = function(){
p.createCanvas(100, 100);
p.background(0);
}
};
new p5(sketch, 'container');
</script>


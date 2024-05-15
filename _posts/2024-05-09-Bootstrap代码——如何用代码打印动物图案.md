---
layout: post
author: jill
---


<p>在帖子中，我们将使用JavaScript在页面上动态创建一个猫的ASCII艺术图案。</p>
<pre>
function printAnimalPattern() {
  // ASCII艺术猫图案
  var cat = `
  /\_/\  
 ( o.o ) 
  > ^ <  
  `;
  // 在页面上创建一个元素来显示图案
  var patternDiv = document.createElement('div');
  patternDiv.innerHTML = cat;
  document.body.appendChild(patternDiv);
}
</pre>
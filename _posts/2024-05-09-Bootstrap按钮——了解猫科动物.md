---
layout: post
author: jill
---

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>猫科知识介绍</title>
<style>
  /* 定义按钮的通用样式 */
  button {
    background-color: #f0f0f0; /* 浅灰色背景 */
    color: #333; /* 深灰色文字 */
    border: none; /* 移除边框 */
    padding: 10px 20px; /* 内边距 */
    cursor: pointer; /* 鼠标指针变为手形 */
    margin: 5px; /* 按钮之间的间隔 */
  }

  /* 定义每个按钮的特定颜色 */
  .general {
    background-color: #ff9900; /* 橙色背景 */
  }

  .behavior {
    background-color: #3399ff; /* 蓝色背景 */
  }

  .vision {
    background-color: #99cc00; /* 绿色背景 */
  }

  .distribution {
    background-color: #ffcc99; /* 浅橙色背景 */
  }
</style>
<script>
function displayFelineFacts(category) {
  var facts = '';
  switch (category) {
    case 'general':
      facts = `
        <h2>猫科动物概述</h2>
        <p>猫科动物是食肉目下的一大类哺乳动物，包括家猫、狮子、老虎等。</p>
      `;
      break;
    case 'behavior':
      facts = `
        <h2>猫科动物的行为</h2>
        <p>猫科动物以其敏锐的捕猎本能、优雅的体态和独特的社会行为而著称。</p>
      `;
      break;
    case 'vision':
      facts = `
        <h2>猫科动物的视力</h2>
        <p>猫科动物的视力在夜晚尤其敏锐，它们的眼睛能够适应低光环境。</p>
      `;
      break;
    case 'distribution':
      facts = `
        <h2>猫科动物的分布</h2>
        <p>猫科动物广泛分布于世界各地，从热带雨林到寒冷的北极地区。</p>
      `;
      break;
    default:
      facts = '<p>请选择一个主题来了解猫科动物的知识。</p>';
  }
  // 在页面上创建一个元素来显示知识
  var factsDiv = document.getElementById('factsDiv');
  factsDiv.innerHTML = facts;
}
</script>
</head>
<body>

<p>点击下面的按钮，选择你想要了解的猫科动物知识主题：</p>

<button class="general" onclick="displayFelineFacts('general')">猫科动物概述</button>
<button class="behavior" onclick="displayFelineFacts('behavior')">猫科动物的行为</button>
<button class="vision" onclick="displayFelineFacts('vision')">猫科动物的视力</button>
<button class="distribution" onclick="displayFelineFacts('distribution')">猫科动物的分布</button>

<div id="factsDiv"></div>

</body>
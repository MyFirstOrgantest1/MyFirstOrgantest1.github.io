---
layout: post
author: ted
---

<style>
  .nav-tabs .nav-link {
    background-color: #4CAF50; /* 绿色背景 */
    color: white; /* 白色文字 */
  }
  .nav-tabs .nav-link.active {
    background-color: #43A047; /* 绿色背景悬停 */
  }
</style>

<body>

<ul id="myTab" class="nav nav-tabs">
	<li class="nav-item active">
		<a class="nav-link" href="#home" data-toggle="tab">
			 动物世界
		</a>
	</li>
	<li class="nav-item dropdown">
		<a class="nav-link dropdown-toggle" href="#" id="myTabDrop1" data-toggle="dropdown">动物分类
			<b class="caret"></b>
		</a>
		<ul class="dropdown-menu" role="menu" aria-labelledby="myTabDrop1">
			<li><a class="nav-link" href="#jmeter" tabindex="-1" data-toggle="tab">哺乳动物</a></li>
			<li><a class="nav-link" href="#ejb" tabindex="-1" data-toggle="tab">鸟类</a></li>
		</ul>
	</li>
</ul>
<div id="myTabContent" class="tab-content">
	<div class="tab-pane fade show active" id="home">
		<p>欢迎来到动物世界！在这里，你可以了解各种动物的生活习性和生态环境。让我们一起探索这个丰富多彩的世界吧！</p>
	</div>
	<div class="tab-pane fade" id="jmeter">
		<p>哺乳动物是一类具有哺乳能力的动物，它们通常具有毛发，以母乳喂养幼崽。常见的哺乳动物包括狗、猫、狮子、老虎等。</p>
	</div>
	<div class="tab-pane fade" id="ejb">
		<p>鸟类是一类具有羽毛和翅膀的动物，它们能够飞行。常见的鸟类包括鸡、鸭、鹰、孔雀等。</p>
	</div>
</div>

</body>
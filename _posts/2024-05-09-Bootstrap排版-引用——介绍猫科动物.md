---
layout: post
author: jill
---

<head>
  <style>
    body, html {
      height: 100%;
      margin: 0;
    }

    .background-image {
      background-image: url('https://cdn.pixabay.com/photo/2017/12/09/21/33/sunset-3008779_1280.jpg');
      background-size: cover;
      background-position: center;
      position: relative; /* 设置相对定位，以便子元素可以绝对定位 */
      width: 100%;
      height: 100vh; /* 使用视口高度 */
    }

    .overlay-text {
      position: absolute; /* 绝对定位，使其位于背景图片上方 */
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%); /* 将元素中心点移动到视口中心 */
      color: white; /* 设置文字颜色为白色 */
      text-align: center; /* 文字居中显示 */
      width: 80%; /* 设置宽度，可以根据需要调整 */
    }
  </style>
</head>
<body>
  <div class="background-image">
    <div class="overlay-text">
      <!-- 默认的引用实例，用于介绍猫科动物 -->
      <blockquote>
        <p>
          猫科动物是食肉目下的一大类哺乳动物，以其敏锐的捕猎本能、优雅的体态和独特的社会行为而著称。这个科包括从小型的家猫到大型的狮子、老虎等。
        </p>
      </blockquote>

      <!-- 带有源标题的引用，引用自某个著名的动物学著作 -->
      <blockquote>
        <p>
          猫科动物的视力在夜晚尤其敏锐，它们的耳朵可以精确地定位声音的来源，这些都是它们作为顶级捕食者的优势。
        </p>
        <small>出自《动物世界百科全书》<cite title="动物世界百科全书">动物世界百科全书</cite></small>
      </blockquote>

      <!-- 向右对齐的引用，描述猫科动物的地理分布 -->
      <blockquote>
        <p>
          猫科动物广泛分布于世界各地，从热带雨林到寒冷的北极地区，都有不同种类的猫科动物生存。
        </p>
        <small>出自《全球野生动物分布图集》<cite title="全球野生动物分布图集">全球野生动物分布图集</cite></small>
      </blockquote>
    </div>
  </div>
</body>

---
layout: post
author: ted
---

<style>
  .form-group label {
    color: #4CAF50; /* 绿色文字 */
  }
  .form-group input {
    border: 1px solid #4CAF50; /* 绿色边框 */
    color: #4CAF50; /* 绿色文字 */
  }
  .form-group input:focus {
    border-color: #4CAF50; /* 绿色边框聚焦 */
  }
  .checkbox label input {
    border: 1px solid #4CAF50; /* 绿色边框 */
    color: #4CAF50; /* 绿色文字 */
  }
  .checkbox label input:focus {
    border-color: #4CAF50; /* 绿色边框聚焦 */
  }
  .btn {
    background-color: #4CAF50; /* 绿色按钮 */
    color: white; /* 白色文字 */
  }
  .btn:hover {
    background-color: #43A047; /* 绿色按钮悬停 */
  }
</style>

<body>

<div class="container">
    <h1>欢迎来到动物王国</h1>
    <h2>登录您的账户</h2>
    <form class="form-horizontal" role="form" style="position: absolute; bottom: 3; left: 1; right: 1;">
      <div class="form-group">
        <label for="firstname" class="col-sm-2 control-label">名字</label>
        <div class="col-sm-10">
          <input type="text" class="form-control" id="firstname" placeholder="请输入名字">
        </div>
      </div>
      <div class="form-group">
        <label for="lastname" class="col-sm-2 control-label">姓</label>
        <div class="col-sm-10">
          <input type="text" class="form-control" id="lastname" placeholder="请输入姓">
        </div>
      </div>
      <div class="form-group">
        <div class="col-sm-offset-2 col-sm-10">
          <div class="checkbox">
            <label>
              <input type="checkbox">请记住我
            </label>
          </div>
        </div>
      </div>
      <div class="form-group">
        <div class="col-sm-offset-2 col-sm-10">
          <button type="submit" class="btn btn-default">登录</button>
        </div>
      </div>
    </form>
</div>

</body>
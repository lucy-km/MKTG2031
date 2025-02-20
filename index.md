---
title: MKTG2031 学习笔记
layout: default
---

# 📖 MKTG2031 学习笔记

**课程内容和 PPT 预览如下：**

<div class="container">
    
  <!-- 左侧：课程 PPT -->
  <div class="left-column">
      <h2>📂 课程 PPT</h2>
      <ul>
          <li><a href="ppt/week1.pptx">第一周 PPT 下载</a></li>
          <li><a href="ppt/week2.pptx">第二周 PPT 下载</a></li>
      </ul>

      <h3>🖥️ 预览课程 PPT</h3>
      <iframe src="https://raw.githubusercontent.com/你的用户名/你的仓库名/main/ppt/week1.pdf" width="100%" height="400px"></iframe>
  </div>

  <!-- 右侧：课程笔记 -->
  <div class="right-column">
      <h2>📌 课程笔记</h2>
      <ul>
          <li><a href="notes/week1.md">第一周笔记</a></li>
          <li><a href="notes/week2.md">第二周笔记</a></li>
      </ul>
  </div>

</div>

---

## **📌 让 CSS 生效**
在 `index.md` 里加入下面的 `<style>` 代码：

```html
<style>
.container {
    display: flex;
    justify-content: space-between;
}

.left-column, .right-column {
    width: 48%;
}

@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
    .left-column, .right-column {
        width: 100%;
    }
}
</style>



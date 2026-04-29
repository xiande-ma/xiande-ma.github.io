---
layout: default
---

<style>
  /* 1. 彻底隐藏系统页眉，确保内容置顶 */
  header, .page-header, .site-header { display: none !important; }
  
  /* 2. 布局：大比例视觉 */
  body {
    background-color: #ffffff !important;
    max-width: 1173px; /* 精准对齐 */
    margin: 0 auto;
    padding: 5px 40px 50px 40px; /* 顶部留白压缩到极致 (5px) */
    color: #000;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    line-height: 1.6;
  }

  /* 3. 导航栏：姓名缩小、不加粗，位置整体上移 */
  .custom-nav {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    border-bottom: 1px solid #eeeeee;
    padding-bottom: 6px;
    margin-bottom: 30px; /* 减小下方间距 */
  }

  .nav-name {
    font-size: 1.35em; /* 进一步缩小姓名，显得更精致 */
    font-weight: 400; /* 纯自然字重，不加粗 */
    color: #000;
    letter-spacing: -0.2px;
  }

  .nav-links {
    font-size: 0.95em;
  }

  .nav-links a {
    text-decoration: none;
    color: #444;
    margin-left: 35px; /* 拉大横向间距，增加大气感 */
    transition: 0.2s;
  }

  .nav-links a:hover { color: #2e6cb2; }

  /* 4. 图片与文字间距优化 */
  .profile-container {
    margin: 10px 0 40px 0;
  }

  .caption {
    color: #bbb;
    font-size: 0.85em;
    margin-top: 10px;
  }

  /* 5. 模块标题：纯黑专业感 */
  h3 {
    margin-top: 45px;
    font-size: 1.25em;
    font-weight: 600;
    color: #000;
  }

  hr { border: 0; border-top: 1px solid #f2f2f2; margin: 35px 0; }
</style>

<div class="custom-nav">
  <span class="nav-name">马先德 (Xiande Ma)</span>
  <div class="nav-links">
    <a href="/">Home</a>
    <a href="/publications">Publications</a>
    <a href="/cv">CV</a>
  </div>
</div>

<div class="profile-container" align="center">
  <img src="child.jpg" width="310" style="border-radius: 2px; box-shadow: 0 5px 25px rgba(0,0,0,0.04);">
  <p class="caption">(Listening for that Nature Communications call... 📞)</p>
</div>

### Hello! 👋
I am a Ph.D. Candidate in the **Materials Science and Engineering (MSE)** Department at **Northeastern University (NEU)**. My research focuses on the atomic-scale origin of pyramidal dislocation slip in magnesium alloys, combining advanced **HAADF-STEM** characterization with **DFT** and **MD** simulations.

---

### Recent News 📰
* **2026/04:** Our research is under review at ***Nature Communications***. 🚀
* **2024/12:** Awarded the **National Scholarship for Doctoral Students**. 🏆
* **2024/08:** Presented a report at the 3rd National Magnesium Resource Utilization Academic Conference. 🎤

---

### Contact ✉️
* **Email**: maxiande@hotmail.com
* **Lab**: Professor Ren Yuping's Group, NEU

---
layout: default
---

<style>
  /* 1. 彻底移除系统默认页眉，消除顶部顽固留白 */
  header, .page-header, .site-header { display: none !important; }
  
  /* 2. 布局：通过增加 max-width 让视野变宽，减少 padding-top 压缩顶部空白 */
  body {
    background-color: #ffffff !important;
    max-width: 1050px; /* 大幅增加宽度，消除手机端浏览感 */
    margin: 0 auto;
    padding: 10px 50px 50px 50px; /* 顶部仅留 10px 极窄空白 */
    color: #000;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    line-height: 1.6;
  }

  /* 3. 导航栏：实现横向拉伸，姓名变小不加粗 */
  .custom-nav {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    border-bottom: 1px solid #eeeeee;
    padding-bottom: 8px;
    margin-bottom: 35px;
  }

  .nav-name {
    font-size: 1.45em; /* 缩小姓名 */
    font-weight: 400; /* 彻底取消加粗 */
    color: #000;
    letter-spacing: -0.2px;
  }

  .nav-links {
    font-size: 0.95em;
  }

  .nav-links a {
    text-decoration: none;
    color: #555;
    margin-left: 30px; /* 拉大链接间距 */
    transition: 0.2s;
  }

  .nav-links a:hover { color: #2e6cb2; }

  /* 4. 图片容器：适度拉开距离 */
  .profile-container {
    margin: 10px 0 45px 0;
  }

  .caption {
    color: #bbb;
    font-size: 0.8em;
    margin-top: 10px;
  }

  /* 5. 模块标题：统一纯黑不浮夸 */
  h3 {
    margin-top: 50px;
    font-size: 1.25em;
    font-weight: 600;
    color: #000;
  }

  hr { border: 0; border-top: 1px solid #f2f2f2; margin: 40px 0; }
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
  <img src="child.jpg" width="300" style="border-radius: 2px; box-shadow: 0 5px 20px rgba(0,0,0,0.03);">
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

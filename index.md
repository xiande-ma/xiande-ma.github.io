---
layout: default
---

<style>
  /* 1. 彻底隐藏默认页眉和横幅 */
  header, .page-header, .site-header { display: none !important; }
  
  /* 2. 核心布局：调整宽度，让内容不再显得“太窄”或“太宽” */
  body {
    background-color: #ffffff !important;
    max-width: 950px; /* 适度拉宽，解决页边距过宽的问题 */
    margin: 0 auto;
    padding: 20px 40px; /* 减小顶部 padding (20px)，解决顶部空白大的问题 */
    color: #444;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    line-height: 1.6;
  }

  /* 3. 导航栏：去掉加粗，保持清爽 */
  .custom-nav {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    border-bottom: 1px solid #eee;
    padding-bottom: 8px;
    margin-bottom: 30px;
  }

  .nav-name {
    font-size: 1.6em;
    font-weight: 500; /* 去掉粗体，改用中等字重 */
    color: #222;
  }

  .nav-links {
    font-size: 1.05em;
  }

  .nav-links a {
    text-decoration: none;
    color: #666;
    margin-left: 15px;
  }

  .nav-links a:hover { color: #2e6cb2; }

  /* 调整图片间距 */
  .profile-container {
    margin: 20px 0 40px 0;
  }
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
  <img src="child.jpg" width="320" style="border-radius: 2px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
  <p style="color: #999; font-style: italic; margin-top: 12px; font-size: 0.9em;">(Listening for that Nature Communications call... 📞)</p>
</div>

### Hello! 👋
I am a Ph.D. Candidate in the **Materials Science and Engineering (MSE)** Department at **Northeastern University (NEU)**. My research focuses on the atomic-scale origin of pyramidal dislocation slip in magnesium alloys, combining advanced **HAADF-STEM** characterization with **DFT** and **MD** simulations.

---

### Recent News 📰
* **2026/04:** Our research is under review at ***Nature Communications***. 🚀
* **2024/12:** Awarded the **National Scholarship for Doctoral Students**. 🏆

---

### Contact ✉️
* **Email**: maxiande@hotmail.com
* **Lab**: Professor Ren Yuping's Group, NEU

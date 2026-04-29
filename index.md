---
layout: default
---

<style>
  /* 1. 彻底隐藏默认的主题页眉，确保页面从最顶端开始 */
  header, .page-header, .site-header { display: none !important; }
  
  /* 2. 核心布局：适度拉宽并调整呼吸感 */
  body {
    background-color: #ffffff !important;
    max-width: 920px; /* 优化后的黄金宽度 */
    margin: 0 auto;
    padding: 25px 45px; /* 减小顶部留白，增加左右纸张感 */
    color: #000000; /* 保持您要求的纯黑字体 */
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    line-height: 1.65;
  }

  /* 3. 导航栏微操：实现“底边对齐”与“空气感” */
  .custom-nav {
    display: flex;
    justify-content: space-between;
    align-items: baseline; /* 确保名字和链接的底边在一条直线上 */
    border-bottom: 1px solid #f0f0f0; /* 极浅的分割线，更显通透 */
    padding-bottom: 12px;
    margin-bottom: 45px;
  }

  .nav-name {
    font-size: 1.6em;
    font-weight: 500; /* 保持自然字重，不加粗 */
    color: #000;
    letter-spacing: -0.2px;
  }

  .nav-links a {
    text-decoration: none;
    color: #666; /* 链接平时略淡，增加层次感 */
    margin-left: 25px;
    font-size: 1em;
    letter-spacing: 0.3px;
    transition: 0.2s;
  }

  .nav-links a:hover { color: #2e6cb2; } /* 悬停时变蓝，增加交互感 */

  /* 4. 图片与说明文字微调 */
  .profile-container {
    margin: 30px 0 50px 0;
  }

  .caption {
    color: #aaaaaa; /* 说明文字调淡，不抢主文戏 */
    font-style: italic;
    margin-top: 15px;
    font-size: 0.85em;
  }

  /* 5. 模块间距优化 */
  h3 {
    margin-top: 55px; /* 增加标题上方的间距，让内容模块化更清晰 */
    font-weight: 600;
    color: #000;
  }

  hr {
    border: 0;
    border-top: 1px solid #f5f5f5;
    margin: 40px 0;
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
  <img src="child.jpg" width="310" style="border-radius: 2px; box-shadow: 0 8px 25px rgba(0,0,0,0.04);">
  <p class="caption">(Listening for that Nature Communications call... 📞)</p>
</div>

### Hello! 👋
I am a Ph.D. Candidate in the **Materials Science and Engineering (MSE)** Department at **Northeastern University (NEU)**. My research focuses on the atomic-scale origin of pyramidal dislocation slip in magnesium alloys, combining advanced **HAADF-STEM** characterization with **DFT** and **MD** simulations.

---

### Recent News 📰
* **2026/04:** Our research on “Atomic-scale origin of pyramidal dislocation slip in magnesium alloys” is under review at ***Nature Communications***. 🚀
* **2024/12:** Honored to receive the **National Scholarship for Doctoral Students**. 🏆
* **2024/08:** Presented a report at the 3rd National Magnesium Resource Utilization Academic Conference. 🎤

---

### Research Interests 🔬
* **Lightweight Alloys**: Magnesium-Rare Earth (Mg-RE) systems.
* **Microstructure**: Interfacial complexion and strengthening mechanisms.
* **Advanced Characterization**: Atomic-resolution STEM imaging and interface superstructures.

---

### Contact ✉️
* **Email**: maxiande@hotmail.com
* **Lab**: Professor Ren Yuping's Group, NEU
* **Location**: Shenyang, China

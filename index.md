---
layout: default
---

<style>
  /* 核心样式：模拟顶级名校个人主页 */
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: #444;
    line-height: 1.7;
    max-width: 1100px; /* 进一步拉宽，减少局促感 */
    margin: 0 auto;
    padding: 40px 60px; /* 增加上下留白，减少左右局促 */
    background-color: #ffffff;
  }

  /* 顶部导航：极致拉开 */
  .header-container {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    border-bottom: 1px solid #f0f0f0;
    padding-bottom: 20px;
    margin-bottom: 50px;
  }

  .name-brand {
    font-size: 2em;
    font-weight: 600;
    color: #222;
    letter-spacing: -0.5px;
  }

  .nav-menu a {
    text-decoration: none;
    color: #888;
    margin-left: 25px;
    font-size: 1.05em;
    transition: color 0.3s;
  }

  .nav-menu a:hover, .nav-menu a.active {
    color: #2e6cb2;
  }

  /* 内容区域排版 */
  h3 {
    font-weight: 600;
    color: #333;
    margin-top: 40px;
    border-left: 4px solid #2e6cb2;
    padding-left: 15px;
  }

  .bio-text {
    font-size: 1.1em;
    color: #555;
    text-align: justify;
  }

  /* 列表美化 */
  ul { padding-left: 20px; }
  li { margin-bottom: 12px; color: #555; }
  b, strong { color: #333; }

  /* 响应式调整 */
  @media (max-width: 768px) {
    .header-container { flex-direction: column; align-items: flex-start; }
    .nav-menu { margin-top: 15px; }
    .nav-menu a { margin-left: 0; margin-right: 20px; }
  }
</style>

<div class="header-container">
  <div class="name-brand">马先德 (Xiande Ma)</div>
  <div class="nav-menu">
    <a href="/" class="active">Home</a>
    <a href="/publications">Publications</a>
    <a href="/cv">CV</a>
    <a href="#contact">Contact</a>
  </div>
</div>

<div align="center" style="margin-bottom: 50px;">
  <img src="child.jpg" width="380" style="border-radius: 2px; filter: grayscale(10%); box-shadow: 0 4px 20px rgba(0,0,0,0.05);">
  <p style="color: #999; font-style: italic; margin-top: 20px; font-size: 0.95em; letter-spacing: 0.5px;">
    (Listening for that Nature Communications call... 📞)
  </p>
</div>

<div class="bio-text">
Hullo! 👋 I am a Ph.D. Candidate in the **Materials Science and Engineering (MSE)** Department at **Northeastern University (NEU)**. My research focuses on the atomic-scale origin of pyramidal dislocation slip in magnesium alloys, combining advanced **HAADF-STEM** characterization with **DFT** and **MD** simulations.
</div>

---

### Recent News 📰

* **2026/04:** Our research on "Atomic-scale origin of pyramidal dislocation slip in magnesium alloys" is under review at ***Nature Communications***. 🚀
* **2024/12:** I was honored to receive the **National Scholarship for Doctoral Students**. 🏆
* **2024/08:** Presented an academic report at the 3rd National Magnesium Resource Utilization Academic Conference.

### Research Interests 🔬

* **Lightweight Alloys**: Magnesium-Rare Earth (Mg-RE) systems.
* **Microstructure**: Interfacial complexion and strengthening mechanisms.
* **Advanced Characterization**: Atomic-resolution STEM imaging.

<div id="contact"></div>

### Contact ✉️

* **Email**: maxiande@hotmail.com
* **Lab**: Professor Ren Yuping's Group, NEU
* **Location**: Shenyang, China

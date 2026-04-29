---
layout: null
---
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xiande Ma | Northeastern University</title>
    <style>
        /* 1. 全局样式：模拟名校个人主页的通透感 */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            color: #3a3a3a; /* 使用陈恩泽同款的高级深灰 */
            line-height: 1.6;
            max-width: 850px; /* 进一步收窄，更有书卷气 */
            margin: 0 auto;
            padding: 50px 30px;
            background-color: #ffffff;
        }

        /* 2. 顶部导航：名字与链接极致拉开 */
        header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            border-bottom: 1px solid #eee;
            padding-bottom: 15px;
            margin-bottom: 40px;
        }

        .name-title {
            font-size: 1.8em;
            font-weight: 700;
            color: #222;
        }

        nav a {
            text-decoration: none;
            color: #666;
            margin-left: 20px;
            font-size: 1.05em;
            transition: color 0.3s;
        }

        nav a:hover { color: #2e6cb2; }

        /* 3. 内容美化 */
        .profile-img {
            display: block;
            margin: 30px auto;
            width: 320px;
            border-radius: 4px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.06);
        }

        h3 {
            font-size: 1.4em;
            font-weight: 600;
            color: #333;
            margin-top: 40px;
            border-bottom: 1px solid #f0f0f0;
            padding-bottom: 8px;
        }

        .bio { font-size: 1.1em; text-align: justify; }

        a { color: #2e6cb2; text-decoration: none; }
        a:hover { text-decoration: underline; }

        .news-list { list-style: none; padding: 0; }
        .news-list li { margin-bottom: 12px; }
        .date { font-weight: bold; color: #555; margin-right: 10px; }
    </style>
</head>
<body>

    <header>
        <div class="name-title">马先德 (Xiande Ma)</div>
        <nav>
            <a href="/">Home</a>
            <a href="/publications">Publications</a>
            <a href="/cv">CV</a>
        </nav>
    </header>

    <img src="child.jpg" alt="Xiande Ma" class="profile-img">
    <p style="text-align: center; color: #999; font-style: italic; font-size: 0.95em;">
        (Listening for that Nature Communications call... 📞)
    </p>

    <div class="bio">
        Hullo! 👋 I am a Ph.D. Candidate in the <b>Materials Science and Engineering (MSE)</b> Department at <b>Northeastern University (NEU)</b>. My research focuses on the atomic-scale origin of pyramidal dislocation slip in magnesium alloys, combining advanced <b>HAADF-STEM</b> characterization with <b>DFT</b> and <b>MD</b> simulations.
    </div>

    <h3>Recent News 📰</h3>
    <ul class="news-list">
        <li><span class="date">2026/04:</span> Our research on "Atomic-scale origin of pyramidal dislocation slip" is under review at <i>Nature Communications</i>. 🚀</li>
        <li><span class="date">2024/12:</span> Honored to receive the <b>National Scholarship for Doctoral Students</b>. 🏆</li>
    </ul>

    <h3>Contact ✉️</h3>
    <p>
        <b>Email:</b> <a href="mailto:maxiande@hotmail.com">maxiande@hotmail.com</a><br>
        <b>Lab:</b> Professor Ren Yuping's Group, NEU<br>
        <b>Location:</b> Shenyang, China
    </p>

</body>
</html>

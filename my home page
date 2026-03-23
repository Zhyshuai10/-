<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人主页 | 赵涵禹的简历</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #2c3e50;
        }
        .lang-buttons {
            text-align: right;
            margin-bottom: 20px;
        }
        button {
            padding: 5px 10px;
            margin-left: 10px;
            cursor: pointer;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #2980b9;
        }
        .section {
            margin-bottom: 20px;
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
        }
        .info {
            background-color: #f9f9f9;
            padding: 10px;
            border-radius: 5px;
        }
        .last-updated {
            font-size: 0.9em;
            color: #777;
            text-align: right;
            margin-top: 20px;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="lang-buttons">
        <button onclick="switchLang('zh')">中文</button>
        <button onclick="switchLang('en')">English</button>
    </div>

    <!-- 中文内容 -->
    <div id="zh-content">
        <h1>赵涵禹</h1>  <!-- 改成您的姓名 -->
        <div class="info">
            <p><strong>学校/专业：</strong> 华东政法大学 经济学专业</p >
            <p><strong>研究兴趣/职业方向：</strong> 会计</p >
            <p><strong>联系方式：</strong> 3427035466@qq.com</p >
        </div>

        <div class="section">
            <h2>个人简介</h2>
            <p>热爱经济学，已通过四六级考试，雅思成绩7.0，善于用Python解决实际问题。乐于学习新技术，团队协作能力强。</p >
        </div>

        <div class="section">
            <h2>技能</h2>
            <ul>
                <li>有较为流畅的英语听说读写能力</li>
                <li>有较好的经济学法学跨学科背景</li>
                <li>擅长学习</li>
                <li>写作与报告</li>
            </ul>
        </div>

        <div class="section">
            <h2>教育经历 / 课程经历</h2>
            <ul>
                <li>华东政法大学 经济学 学士(2024-2028)</li>
                <li>核心课程：微观经济学 宏观经济学 计量经济学 政府经济学 </li>
            </ul>
        </div>

        <div class="last-updated" id="zh-date">
            最后更新日期：2026年3月23日
        </div>
    </div>

    <!-- 英文内容 -->
    <div id="en-content" style="display: none;">
        <h1>Hanyu Zhao</h1>
        <div class="info">
            <p><strong>University/Major:</strong> ECUPL, economy</p >
            <p><strong>Research Interest/Career Direction:</strong> bookkeeper</p >
            <p><strong>Contact:</strong>3427035466@qq.com</p >
        </div>

        <div class="section">
            <h2>Profile</h2>
            <p>Enthusiastic about economy, skilled in solving real-world problems with Python. Quick learner and strong team player.</p >
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li> Fluent English listening, speaking, reading and writing skills.</li>
                <li>Strong interdisciplinary background in Economics and Law</li>
                <li>Econometrics / Statistics</li>
                <li>Writing & Reporting</li>
            </ul>
        </div>

        <div class="section">
            <h2>Education / Courses</h2>
            <ul>
                <li>East China University of Political Science and Law, Bachelor of Economics (2024–2028)</li>
                <li>Key Courses: Data Structures, Machine Learning, Big Data Analytics</li>
            </ul>
        </div>

        <div class="last-updated" id="en-date">
            Last Updated: March 23, 2026
        </div>
    </div>
</div>

<script>
    function switchLang(lang) {
        if (lang === 'zh') {
            document.getElementById('zh-content').style.display = 'block';
            document.getElementById('en-content').style.display = 'none';
        } else {
            document.getElementById('zh-content').style.display = 'none';
            document.getElementById('en-content').style.display = 'block';
        }
    }
    // 默认显示中文
    switchLang('zh');
</script>
</body>
</html>

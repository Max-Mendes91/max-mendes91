<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Max's GitHub Profile - Preview</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            padding: 40px 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 40px;
        }

        h1 {
            color: #58a6ff;
            font-size: 2.5em;
            margin-bottom: 15px;
        }

        h2 {
            color: #58a6ff;
            font-size: 1.5em;
            margin-top: 30px;
            margin-bottom: 15px;
            border-bottom: 1px solid #21262d;
            padding-bottom: 8px;
        }

        .badge {
            display: inline-block;
            margin-bottom: 20px;
        }

        .intro {
            font-size: 1.05em;
            margin-bottom: 30px;
            color: #8b949e;
        }

        .stats-box {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
            font-size: 0.9em;
        }

        .stats-box pre {
            color: #c9d1d9;
            overflow-x: auto;
        }

        ul {
            list-style: none;
            padding-left: 0;
        }

        ul li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }

        ul li:before {
            content: "▹";
            position: absolute;
            left: 0;
            color: #58a6ff;
            font-weight: bold;
        }

        .tech-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .contact-badges {
            display: flex;
            gap: 15px;
            margin-top: 15px;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #21262d;
            color: #8b949e;
            font-style: italic;
        }

        em {
            color: #58a6ff;
            font-style: italic;
        }

        .copy-section {
            background: #238636;
            border-radius: 6px;
            padding: 15px;
            margin-top: 30px;
            text-align: center;
        }

        .copy-button {
            background: #fff;
            color: #238636;
            border: none;
            padding: 12px 24px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            transition: all 0.2s;
        }

        .copy-button:hover {
            background: #f0f0f0;
            transform: scale(1.05);
        }

        .copy-button:active {
            transform: scale(0.98);
        }

        .success-message {
            display: none;
            color: #fff;
            margin-top: 10px;
            font-weight: 500;
        }

        .markdown-code {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 15px;
            margin-top: 20px;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
            font-size: 0.85em;
            max-height: 500px;
            overflow-y: auto;
            white-space: pre;
            color: #c9d1d9;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi, I'm Max 👋</h1>
        
        <div class="badge">
            <img src="https://wakatime.com/badge/user/5f357981-1e66-44ef-ae81-f181857a2d5e.svg" alt="wakatime">
        </div>

        <p class="intro">
            Web development learner building projects and exploring modern web development. Improving daily through hands-on projects and sharing my journey here on GitHub.
        </p>

        <h2>⏱ Coding Stats</h2>
        <div class="stats-box">
            <pre>JavaScript   40 hrs 6 mins   ██████████████████████░░░   87.77 %
HTML         1 hr 22 mins    ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.02 %
CSS          1 hr 20 mins    ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.95 %
TypeScript   1 hr 7 mins     ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.47 %
Markdown     33 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.22 %</pre>
        </div>

        <h2>🚀 Current Focus</h2>
        <ul>
            <li>Practicing fundamentals with interactive mini-games (e.g., <em>Guess My Number</em>)</li>
            <li>Strengthening DOM manipulation and styling skills</li>
            <li>Building responsive layouts and experimenting with UI/UX improvements</li>
        </ul>

        <h2>🛠️ Tools & Technologies</h2>
        <div class="tech-badges">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
            <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
            <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
            <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
        </div>

        <h2>🎯 Next Steps</h2>
        <ul>
            <li>More polished project deployments (GitHub Pages)</li>
            <li>Expanding into frameworks (React.js) in the near future</li>
            <li>Sharpening problem-solving and clean coding practices</li>
        </ul>

        <h2>📫 Connect with Me</h2>
        <div class="contact-badges">
            <a href="https://portfolio-react-omega-bice.vercel.app/" target="_blank">
                <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
            </a>
            <a href="https://www.linkedin.com/in/max-mendes-776ab5212/" target="_blank">
                <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
            </a>
        </div>

        <div class="footer">
            💡 <em>Always learning, always building</em>
        </div>

        <div class="copy-section">
            <button class="copy-button" onclick="copyMarkdown()">📋 Copy README.md Code</button>
            <div class="success-message" id="successMsg">✓ Copied to clipboard!</div>
        </div>

        <div class="markdown-code" id="markdownCode"># Hi, I'm Max 👋

[![wakatime](https://wakatime.com/badge/user/5f357981-1e66-44ef-ae81-f181857a2d5e.svg)](https://wakatime.com/@5f357981-1e66-44ef-ae81-f181857a2d5e)

Web development learner building projects and exploring modern web development. Improving daily through hands-on projects and sharing my journey here on GitHub.

## ⏱ Coding Stats
<!--START_SECTION:waka-->
```txt
JavaScript   40 hrs 6 mins   ██████████████████████░░░   87.77 %
HTML         1 hr 22 mins    ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.02 %
CSS          1 hr 20 mins    ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.95 %
TypeScript   1 hr 7 mins     ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.47 %
Markdown     33 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.22 %
```
<!--END_SECTION:waka-->

## 🚀 Current Focus

- Practicing fundamentals with interactive mini-games (e.g., *Guess My Number*)
- Strengthening DOM manipulation and styling skills
- Building responsive layouts and experimenting with UI/UX improvements

## 🛠️ Tools & Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 🎯 Next Steps

- More polished project deployments (GitHub Pages)
- Expanding into frameworks (React.js) in the near future
- Sharpening problem-solving and clean coding practices

## 📫 Connect with Me

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-react-omega-bice.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/max-mendes-776ab5212/)

---

💡 *Always learning, always building*</div>
    </div>

    <script>
        function copyMarkdown() {
            const markdownText = document.getElementById('markdownCode').textContent;
            navigator.clipboard.writeText(markdownText).then(() => {
                const successMsg = document.getElementById('successMsg');
                successMsg.style.display = 'block';
                setTimeout(() => {
                    successMsg.style.display = 'none';
                }, 2000);
            });
        }
    </script>
</body>
</html>

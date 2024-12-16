# krita ai 启动器

![image](https://github.com/user-attachments/assets/7ff74400-61e7-4fb8-9ef3-ff231f8c97e9)

这一款


<!-- 多语言切换示例 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-language Markdown</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .language-button {
            margin: 10px;
            padding: 5px 15px;
            cursor: pointer;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .language-button:hover {
            background-color: #eaeaea;
        }
        .content {
            display: none;
        }
        .content.active {
            display: block;
        }
    </style>
</head>
<body>
    <div>
        <button class="language-button" onclick="switchLanguage('english')">English</button>
        <button class="language-button" onclick="switchLanguage('chinese')">中文</button>
    </div>
    
    <div id="english" class="content active">
        <h1>Welcome</h1>
        <p>This is the English version of the content.</p>
    </div>
    
    <div id="chinese" class="content">
        <h1>欢迎</h1>
        <p>这是中文版本的内容。</p>
    </div>

    <script>
        function switchLanguage(language) {
            const contents = document.querySelectorAll('.content');
            contents.forEach(content => {
                if (content.id === language) {
                    content.classList.add('active');
                } else {
                    content.classList.remove('active');
                }
            });
        }
    </script>
</body>
</html>

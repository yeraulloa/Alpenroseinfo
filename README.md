<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Il Mio Sito</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .language-selector { margin-bottom: 20px; }
    </style>
</head>
<body>
    <div class="language-selector">
        <select id="language" onchange="changeLanguage()">
            <option value="it">Italiano</option>
            <option value="en">English</option>
            <option value="es">Español</option>
            <option value="de">Deutsch</option>
            <option value="zh">中文</option> <!-- Cinese -->
            <option value="sr">Српски</option> <!-- Serbo -->
            <option value="fr">Français</option> <!-- Francese -->
            <option value="ru">Русский</option> <!-- Russo -->
        </select>
    </div>

    <div id="content">
        <h1 id="title">Benvenuto nel mio sito</h1>
        <p id="description">Questa è una descrizione di esempio in italiano.</p>
    </div>

    <script>
        const content = {
            it: {
                title: "Benvenuto nel mio sito",
                description: "Questa è una descrizione di esempio in italiano."
            },
            en: {
                title: "Welcome to My Website",
                description: "This is a sample description in English."
            },
            es: {
                title: "Bienvenido a Mi Sitio Web",
                description: "Esta es una descripción de ejemplo en español."
            },
            de: {
                title: "Willkommen auf meiner Website",
                description: "Dies ist eine Beispielbeschreibung auf Deutsch."
            },
            zh: {
                title: "欢迎来到我的网站",
                description: "这是一个中文示例描述。"
            },
            sr: {
                title: "Добродошли на мој сајт",
                description: "Ово је пример описa на српском."
            },
            fr: {
                title: "Bienvenue sur mon site",
                description: "Ceci est une description d'exemple en français."
            },
            ru: {
                title: "Добро пожаловать на мой сайт",
                description: "Это пример описания на русском."
            }
        };

        function changeLanguage() {
            const lang = document.getElementById('language').value;
            document.getElementById('title').innerText = content[lang].title;
            document.getElementById('description').innerText = content[lang].description;
        }
    </script>
</body>
</html>
</body>
</html>
<img src="https://tinypic.host/image/%28Inglese%29.2fsAq6
https://tinypic.host/image/1.2fsFJM
https://tinypic.host/image/2.2fsXJh
https://tinypic.host/image/3.2fs461
https://tinypic.host/image/4.2fsbVG
https://tinypic.host/image/5.2fstoz
https://tinypic.host/image/6.2fszbU
https://tinypic.host/image/7.2fsQD2
https://tinypic.host/image/8.2fs0P4
https://tinypic.host/image/10.2fs6Mf
https://tinypic.host/image/11.2fscZk
https://tinypic.host/image/12.2fsWOx" alt="Descrizione del design">

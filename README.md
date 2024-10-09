# Alpenroseinfo
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

AntiCor AI KZ — версия для GitHub Pages

ШАГИ:
1. Распакуйте ZIP.
2. Откройте github.com и создайте публичный репозиторий AntiCor-AI-KZ.
   Если репозиторий с таким именем уже есть, можно загрузить файлы туда.
3. В репозитории выберите Add file -> Upload files.
4. Загрузите СОДЕРЖИМОЕ распакованной папки в КОРЕНЬ репозитория.
   В корне должны находиться index.html, app.js, styles.css,
   папки assets, data и файл .nojekyll.
5. Нажмите Commit changes.
6. Settings -> Pages -> Build and deployment -> Deploy from a branch.
7. Branch: main; folder: /(root); нажмите Save.
8. Ожидаемый адрес: https://USERNAME.github.io/AntiCor-AI-KZ/

ВАЖНО: GitHub Pages размещает только статический сайт.
Главная страница, учебные кейсы и тесты работают в браузере.
Настоящий ИИ через OpenAI или Ollama там не запускается.
Для онлайн-ИИ нужен отдельный сервер/API, а API-ключ нельзя хранить в коде браузера.
Не загружайте файл .env с секретами в публичный репозиторий.

Для запуска проекта:
1. клонировать репозиторий (git clone https://github.com/AndreiDudenkov/project_for_iOS)
2. открыть проект в своей IDE
3. установить зависимости (npm install). Версия node v18.15.0 Версия npm 9.5.0
4. запустить проект (npm run start) 
5. для просмотра макетов изменить URL в браузере на:
http://localhost:3000/index.iPhone_8.html?lang=en для iPhone SE, 8+
http://localhost:3000/index.iPhone_13.html?lang=en для iPhone 11 pro, 14, 14 plus, 14 pro max
6. для изменения зыковых параметров изменить язык самого браузера или URL (например: http://localhost:3000/index.iPhone_13.html?lang=es)

Проект сверстан под English, работает автоопределение языка с настроек браузера и с URL, для смены языка.
Использован сборщик Gulp.
На других языках в некоторых местах верстка 'плывет'.

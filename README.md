### Стартовый шаблон для разработки интерфейса

1. Переходим в папку с шаблоном: ``` cd template-project/ ```
2. Устанавливаем зависимости bower: ```bower install``` 
3. Устанавливаем зависимости gulp: ```npm install``` 
4. Подключаем скаченные компоненты bower в app/index.html: ```gulp bower``` 
5. Проект собирается в dist/ после команды: ```gulp build```  
6. Следит за изменениями в app/ файлов js, css, html: ```gulp watch```.

> Установлен препроцессор less, после компиляции стили находятся в app/css/main.css и подключены в app/index.html.

#### bower dependencies:
    "jquery": "^3.0.0",
    "normalize-css": "normalize.css#^4.2.0",
    "tooltipster": "^4.0.4"

#### gulp devDependencies:
    "browser-sync": "^2.13.0",
    "gulp": "^3.9.1",
    "gulp-autoprefixer": "^3.1.0",
    "gulp-clean": "^0.3.2",
    "gulp-if": "^2.0.1",
    "gulp-less": "^3.1.0",
    "gulp-minify-css": "^1.2.4",
    "gulp-rename": "^1.2.2",
    "gulp-sftp": "^0.1.5",
    "gulp-uglify": "^1.5.4",
    "gulp-useref": "^3.1.0",
    "wiredep": "^4.0.0"

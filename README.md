# Проект: Калькулятор
Посмотреть проект можно по ссылке - [https://test.teatlt.ru/calc/](https://test.teatlt.ru/calc/)

На проекте используется сборка Webpack 4 и имеет два файла конфигурации:
1.	**webpack.dev.js** –  конфигурация для разработки, собранный проект кладет в папку ./dist/dev, не сжимает, source maps присутствует.
В *index.html* выводиться сообщение «Development mode» в заголовке `<h1>` (для этого используется плагин *HtmlWebpackPlugin*).
Для запуска используется команда – `npm run build:dev`
2.	**webpack.prod.js** – конфигурация для выгрузки на сервер, собранный проект кладет в папку ./dist/prod, сжимает файлы .css и .js, source maps удалены.
В *index.html* выводиться сообщение «Production mode» в заголовке `<h1>` (для этого используется плагин *HtmlWebpackPlugin*).
Для запуска используется команда – `npm run build:dev`


В Webpack подключен транспайлер BabelJS.


***
####ES6 в проекте.

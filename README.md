test
====

Структура верстки:

1. index.html - хтмл страницы

2. папка less - все файлы для работы с LESS: struct.less - основной файл стилей, elements.less - стандартный набор стилей

3. папка css - в ней размещаются дефолтные стили для браузеров в папке core, стили для адаптивного дизайна в папке media, скомпилированный из less файл стилей struct.css, файл стилей для ие8 (ie8.css), для редактора (editor.css) и файл main.css объединяет все файлы со стилями и подключается в шапку index.html

4. папка font - дизайнерские шрифты

5. папка pic - разделяется на картинки подключенные через html (pic_html) и через css (pic_css)

6. папка script - в ней подключаем основные скрипты (core) - такие как jquery, html5 и плагины (plugins) - скроллы, слайдеры, ротаторы и т.д, в файл settings.js - записываем вызовы функций, плагинов и свои js скрипты. settings-ie.js - соответственно для ие.

В ие9+ не проверила верстку, т.к. на домашнем ноутбуке стоит ие8)
По времени - приблизительно 1,5 дня.
GitHub раньше не использовала, работала только с свн-ом.

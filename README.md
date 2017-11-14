TESTING WORK IN GIT
=====================

Полезные ссылки
-----------------------------------

1. [Базовый интенсив по JavaScript](https://up.htmlacademy.ru/javascript/11)
2. [Шапргалка по GIT](http://dev-lab.info/2013/08/%D1%88%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0-%D0%BF%D0%BE-git-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD/)
3. [Как оформить README.md](http://webdesign.ru.net/article/pravila-oformleniya-fayla-readmemd-na-github.html)
4. [Статьи для WebДизайна](https://smartia.me/profession/webdesigner/)
5. [GitHowTo](https://githowto.com/ru)
6. [Официальный учебник по Git](https://git-scm.com/book/ru/v2)

Как я добавил этот файл сюда
-----------------------------------

1. Запускаем **Git Bash**
2. Вводим
    сd d:/MyFiles/Projects/Other/нужная_дериктория`
3. Вводим команду `git init` если нужно создать репозиторий. В ином случае пропускаем этот пункт.
4. Редактируем необходимый файл (в данном случае README.md)
5. Индексируем его
    git add README.md
6. Закрепляем/сохраняем изменения/коммиттим
    git commit -m "Название коммита латинницей"
7. Загружаем измененный файл (или прописываем путь для него, я не совсем понял что я тут сделал, возможно это требуется ввести только один раз для данного репозитория)
    git remote add origin http://github.com/DrakDim/workspace.git/
8. Вот теперь видимо загружаем сделанные изменения на GitHub (потому что от меня потребовали ввести свои данные для входа в GitHub аккаунт)
    git push -u origin master

Зона тестирования
-----------------------------------

Тестирование заголовка
----

    dir /fonts
    dir /images
    dir /js

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

```php
<?php here_pagecontent(); ?>
```

```scss /* или css */
@import "bower_components/tree-normalize/generic.normalize";
h1 {
 font-size:1.5em;
 font-weight: 300;
}
```

> Текст
> 
> Продолжение текста выделенного блока
> _наклонный_ _шрифт_ **Жирный шрифт** ***Наклонный жирный*** `выделенные слова`
> Завершение текста
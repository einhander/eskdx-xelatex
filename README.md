XeTeX ЕСКД Заготовка
====================

Главная цель этой заготовки — что бы с помощью неё можно было легко и
быстро создавать ЕСКД документацию, в основном дипломы, диссертации, пояснительные записки, курсовые — то, что нужно при учёбе в ВУЗе. Заготовка основана на пакете [eskdx](http://eskdx.org.ua/).

Что внутри?
-----------

 - Настроена работа с русским языком, кириллическими шрифтами;
 - Сделана заготовка для заполнения параметров eskdx-пакета; 
 - Используются стандартные пакеты, которые скорее всего понадобятся во время работы;
 - Заготовка для документа;
 - Заготовка для библиографии;
 - Несколько «хаков», что бы всё работало;
 - Всё с комментариями;
 - Добавлен шрифт ГОСТ тип А, на который настроен шаблон;
 - Добавлена поддержка автоматического определения компилятора для Texstudio.

Установка
---------

Что бы использовать заготовку скачайте её. В файле `input/header.tex` есть команды подгружающие пакеты (`\usepackage`). Нужно что бы все эти пакеты были установлены (здесь поможет google).
В скачанной папке запустите комманду `$ xelatex document.tex`. Файл должен скомпилироваться в файл `document.pdf`.

Полезные руководства для начинающих
-----------------------------------

 -  [С. М. Львовский. Набор и вёрстка в системе LaTeX](http://www.mccme.ru/free-books/llang/newllang.pdf)
 -  [Руководство пользователя ESKDx](http://eskdx.org.ua/downloads/eskdx-0.98.pdf)
 -  [Примеры использования ESKDx](http://eskdx.org.ua/wiki/%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D1%8B%D0%98%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8FEskdx)
 

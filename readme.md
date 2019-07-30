About
----------------------------
Web-приложение математический чат позволяет в рамках общения в чате передавать и получать формульную информацию
 с возможностью ее графического отображения. Разработанная программа позволяет обмениваться 
 формульной информацией в реальном времени без необходимых знаний языка разметки TeX, 
 на котором происходит общение для отображения формул.

Данное web-приложение позволяет пользователям, не имеющим специальных знаний в языке разметки TeX, использовать 
соответствующую панель с изображениями математических символов для выбора необходимого 
элемента формулы, чтобы добавить разметку в поле ввода информации при нажатии.

Functions
-----------------------------
Для реализации необходимой указанной функциональности реализовано следующие алгоритмы:
* Скрытие и отображение изображений символов на панели формы отправки.
* Вставка кода разметки на языке TeX в поле для ввода после нажатия на элемент с изображением.
* Отправка сообщения с последующим рендерингом кода разметки в HTML код.
* Обмен сообщениями в реальном времени.

View
-----------------------------

![Иллюстрация к проекту](https://github.com/IHolovach/parseedit/blob/master/images/chatview.png)
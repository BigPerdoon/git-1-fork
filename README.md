# Курсовой проект к модулю "Введение в тестирование"

## Правила выполнения курсового проекта

- Объект тестирования: интернет-магазин https://henderson.ru.
**Важно:** это реальный сайт, НЕ ТЕСТОВЫЙ, поэтому не надо совершать на нем покупки и прочие подобные действия.
- Скопируйте шаблон таблицы на свой Google-диск [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing), укажите в названии файла свои фамилию, имя и группу вместо Name, Surname, Group. Проверьте настройки доступа в своем документа – чтобы в ваших гугл-документах и таблицах была открыта возможность комментировать всем пользователям в интернете, кому предоставлена ссылка.
- В предоставленном шаблоне есть все шаблоны чек-листов для тестирования, которые нужны для выполнения задания.
- В своей таблице прикрепляйте ссылки на результаты тестирования по каждому заданию.
- Вам необходимо выполнить 5 заданий, кроме задания со звездочкой (задание 3.2* выполняется по желанию).
- Когда выполните все 5 заданий, прикрепите в личном кабинете ссылку на свою таблицу с решениями и ожидайте проверки преподавателя.
- Курсовой проект считается принятым, когда все 5 заданий (кроме задания 3.2.* по желанию) приняты преподавателем.

## Задание 1

Написать чек-лист для функциональной проверки [личного кабинета зарегистированного пользователя](https://henderson.ru/cabinet/) (включая функционал разделов) на сайте https://henderson.ru/.

**Требования к выполнению:**
* Чек-лист должен представлять собой структурированный (многоуровневый) список, который содержит набор позитивных и негативных проверок компонентов объекта тестирования.
* При составлении списка проверок должны учитываться различные варианты состояний страниц. Например, при проверке функционала "Мои отзывы" мы проверяем не только состояние без отзывов, но и с ними.
* Мы ожидаем от вас проверку функционала личного кабинета без учета хедера и футера страницы, то есть то, что есть в этой [области](https://prnt.sc/112e3e7).

## Задание 2

Необходимо написать набор тест-кейсов на проверку функционала восстановления пароля.

Ваша задача - написать минимум 20 тест-кейсов, которые должны покрывать все, что описано в требованиях по
[ссылке](https://docs.google.com/document/d/12deDbATIy0Xps8MiWvumNqHISfAlFc4etY8F4lPcqJ4/edit?usp=sharing), и учитывать позитивные и негативные кейсы.


## Задание 3

3.1. На основе [скриншота](https://prnt.sc/114niqm) создать не менее трех баг репортов.

3.2*. Найти баг в функционале "Написать отзыв" в карточке товара и составить на него баг-репорт. 
Если найдете несколько - замечательно!

## Задание 4

Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте в данный момент товаров с такой ценой нет, а разработчик бекенда в отпуске, поэтому вам нужно протестировать верстку страницы карточки товара с максимальной и минимальной ценой самостоятельно.
Ваша задача - самостоятельно определить, как проще это реализовать, и предоставить решение в виде скриншотов страницы карточки товара с минимальной и максимальной ценой товара.

## Задание 5

Бекенд разработчик говорит, что мы отправляем данные с сайта в неправильном формате и просит вас помочь найти нужный запрос. Фронтенд разработчик ушел в отпуск в поход без связи, а документация пропала.

Известно, что проблема в данных, которые уходят в post запросе по адресу https://api.mindbox.ru/v3/js/operations/sync, и происходит это скорее всего при работе с личными данными пользователя (например авторизация, личный кабинет, просмотр корзины).

Ваша задача - изучить ответы и запросы при работе с сайтом; найти, как же выглядят параметры deviceUUID, requestId и status, и приложить скриншот искомого превью в таблицу с решениями.

### Как правильно задавать вопросы преподавателю?

Что поможет решить большинство частых проблем:

1. Попробовать найти ответ сначала самому в интернете и только после этого спрашивать у преподавателя. Скилл поиска ответов пригодится вам в профессиональной деятельности.
1. Если вопросов больше одного, то присылайте их в виде нумерованного списка. Так преподавателю будет проще отвечать на каждый из них. 
1. При необходимости прикрепите к вопросу скриншоты и стрелочкой покажите, где не получается. Программу для этого можно скачать здесь [https://app.prntscr.com/ru/](https://app.prntscr.com/ru/)

Что может стать источником проблем:

1. Вопросы вида «Ничего не работает. Не запускается. Всё сломалось». Преподаватель не сможет ответить на такой вопрос без дополнительных уточнений. Цените своё время и время других.
2. Откладывание выполнения курсового проекта на последний момент.
3. Ожидание моментального ответа на свой вопрос. Преподаватели - работающие разработчики, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы :)

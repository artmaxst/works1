# Домашнее задание к занятию 1.1. «Введение в тестирование ПО. Методы и виды тестирования»

Прочтите описание ситуаций, в которых работает тестировщик. Подумайте, какой вид или уровень тестирования стоит применить в каждой из ситуаций. Возможно, надо применить несколько.



## Список ситуаций:

1. Наша команда разработки делает новый сайт, на котором мы сможем смотреть фильмы. Но пока дизайнеры не решили, как будет выглядеть сам сайт, и разработчик сделал только видеоплеер, который мы потом будем использовать. Какой вид или уровень тестирования мы будем применять, если хотим протестировать отдельно этот просмотрщик?

2. Команда разработки систем оплаты сервиса, в котором мы работаем, вместе с новым провайдером интернета сделала новую фишку — при покупке месяца интернета пользователь получает полгода подписки в нашем сервисе в подарок. Наша задача — применить подходящий вид или уровень тестирования для этой ситуации. 

3. Наш банк решил сделать приложение для детей, которые учатся пользоваться банковскими картами. Мы целый год его создавали, старались, и вот, наконец, сборка готова, интеграционные тесты пройдены. Всё, казалось бы, работает, и мы почти готовы к настоящему первому релизу в прод. Но перед этим осталось провести самую большую серьёзную проверку. Что же мы применим?

4. Наша компания делает расширение для браузера, которое помогает переводить слова на странице. Но некоторые пользователи почему-то жалуются, что при обновлении версии расширения оно перестаёт переводить. Что же применить?

5. Дизайнеры решили, что наш дизайн управления банковскими переводами устарел, прошло несколько месяцев, и мы зарелизили новый. Но после этого в техническую поддержку начали писать разозлённые пользователи: говорят, что невозможно найти кнопку создания нового перевода, а если и получается её найти, ткнуть на неё невозможно. Но как так, ведь всё было по техническому заданию! Придётся протестировать сервис ещё раз с этим видом тестирования, чтобы понять, почему пользователям неудобно.

6. Мы узнали, что через неделю отдел маркетинга будет делать обширную пиар-кампанию сервиса, который мы тестируем. Наш руководитель сказал, что нужно провести тестирование, показывающее, что наш сайт справится с нагрузкой, которая, предположительно, будет больше нашей обычной в 10 раз. Какой же вид тестирования мы будем проводить?

7. Представим, что мы делаем новостной сайт и зарабатываем на рекламе. Но наши аналитики говорят, что не все пользователи её видят. После проверки мы поняли, что в некоторых браузерах встроено отключение рекламы, но мы не знаем точно, в каких и как она работает так, что не видно наши баннеры. Какое тестирование мы проведём, чтобы понять, где именно не работает функционал?

8. Разработчику поступила задача добавить события аналитики к основным возможностям программы. Перед тем как отдать программу на проверку тестировщику, после изменений разработчик проверяет весь основной функционал на работоспособность. Какой вид тестирования выполняет разработчик?

9. Представим, что мы выпускаем наш сайт с новыми функциями. Он уже протестирован, все новинки работают, но перед тем как выпускать его на всех пользователей, нам нужно проверить, не сломался ли старый функционал — вдруг новые изменения его затронули.

10. Мы работаем в компании, которая делает мобильное приложение. Поздний вечер, все разошлись, и разработчик перед уходом прислал нам на тест сборку с новым функционалом, который он только что сделал. Нам хочется понять, готова ли сборка к полноценному тестированию сегодня. Мы устанавливаем её на телефон, приложение запускается, но нужных нам новых функций почему-то нет. Что ж, сегодня мы уже не сможем протестировать его задачу. Какое тестирование помогло нам понять, что пора и нам уже домой?  

11. Разработчик добавил новые возможности на сервере, и теперь сервер умеет отвечать на три новых запроса к нему. Чтобы понять, надо ли приступать к полной проверке с негативными, позитивными и прочими сценариями, мы проверили, что сервер действительно отвечает на эти три запроса, если всё сделать как в техническом задании. Какое тестирование мы провели?

## `*` Дополнительная задача более сложного уровня

Есть реальная ситуация из опыта лектора, на основе которой надо сделать выводы на 2–3 предложения. Идеального правильного ответа нет, важно, чтобы вы задумались, как вообще можно применять материал, пройденный на первом занятии.

Мы работаем в компании, которая делает сервис для чтения книг в приложении. Мы можем добавлять книги в свою библиотеку, читать, слушать несколько книг по очереди и так далее — стандартный набор. Но к нам стали поступать жалобы на то, что пользователь не может выйти из текста книги назад, на её описание. Мы удивились, провели проверки, посмотрели на разных устройствах, но у нас всё работает. 

Но, увидев эти отзывы в AppStore и GooglePlay, мы поняли, что, возможно, проблема в чём-то ещё. В чём же?

Отзывы из сторов:

*Вопрос к функционалу приложения*

*К подписке вопросов нет, интересующие книги вроде бы есть, однако есть одно но — функционал приложения. Дорогие разработчики, как мне закрыть книгу, чтобы, например, посмотреть что-то другое? Справляюсь следующим образом: удаляю приложение и устанавливаю его заново.*

*Премиум подписка не стоит своей цены!*

*Ужасное приложение! Находясь в книге, нереально выйти в головное меню и подобрать и читать другие книги или сделать что-то ещё.*

*Баг*

*Очень интересная проблема возникла: после открытия книги нет возможности из неё выйти, даже когда перезагружаю приложение, всегда открывается книга, которую я не хочу читать, выйти из чтения никак не могу.*

*Сложности с выходом из книги даже перезапуск приложения не помогает.*


Какие методики из пройденного материала стоило бы использовать более продуктивно, чтобы так не подвести своих пользователей? 
Опишите эти виды и поясните, почему вы выбрали именно их. Если есть какие-то идеи, помимо описанных в лекции, расскажите и их тоже. Помните, что наша цель — не только проверить, усвоился ли материал, но и попробовать представить себя в типичной для специалиста по качеству ситуации.


# Решение:
[Задание 1](https://github.com/artmaxst/iqa-homeworks1/blob/3037277a5f00b135302ef2d4807da86fb0be3677/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201.pdf)

[Дополнительная задача*](https://github.com/artmaxst/iqa-homeworks1/blob/3037277a5f00b135302ef2d4807da86fb0be3677/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201.1.(_).pdf)

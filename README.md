# DPO_Python_2023
# Материалы по курсу «Python для автоматизации и анализа данных» (НИУ ВШЭ, ЦНО ФКН).

Преподаватель: Ян Пиле

## Общая информация:
Каждому занятию соответствует свой порядковый номер. Всего занятий 18 (12 - программирование на Python, 6 - Python для анализа данных). В папке каждого занятия вы найдете блокноты с пройденным на семинаре материалом и иногда ссылки на дополнительные материалы.

Где можно и нужно решать задачи: https://leetcode.com/problemset/all/

## Блок 1. Python

1 занятие (14.02.2023)
[Гид по git. Стиль PEP8. Основы работы с Jupyter. Целые и вещественные числа, логические переменные. Строки, ввод и форматирование](https://github.com/pileyan/DPO_Python_2023/tree/master/lect01_git_basic_types)

2 занятие (18.02.2023)
[Контейнеры в Python: списки, кортежи, множества, словари. Индексация и срезы. Методы строк и списков.Условный оператор.](https://github.com/pileyan/DPO_Python_2023/tree/master/lect02_complex_types_if_else)


## Формы контроля
Всего на курсе запланировано 5 дз в блоке "Программирование на Python" (включая финальный проект. Он большой.) и 4 дз в блоке "Python для анализа данных".

Всего на курсе ~ 9 заданий (включая проект), для получения зачета по этой части программы нужно иметь среднюю оценку не менее 4 из 10 (из расчета всех заданий по курсу, не только выполненных).

Лабораторная работа - это формат решения заданий в классе. Это не самостоятельная работа - вы можете задавать преподавателю вопросы по ходу решения. Решенные задачи будут проверяться прямо в классе. Если вы пропустили занятие или не успели сделать нужное количество заданий на семинаре, то всегда можно загрузить файл по ссылке на Dropbox к определенному дедлайну. Ссылка, информация о дедлайне и количестве выполненных заданий, необходимых для зачета по работе, будет публиковаться в конце этого файла + мы будем дублировать информацию в чат группы в Telegram.

Оценки за задания выставляются в 10-балльной шкале. Чтобы получить зачет по курсу/сертификат, необходимо иметь среднюю оценку за задания не ниже 4 баллов (из расчета всех заданий по курсу, не только выполненных). Ориентировочный срок выполнения задания - 1 неделя +- 1-2 дня. 
За сдачу заданий после дедлайна предусмотрен штраф 40% (максимальный балл за задание будет не 10, а 6). Исключение составляет задание про Телеграм-бота - оно более объемное и имеет относительно свободную формулировку, поэтому на него будет выделено ~ 2.5 недели. 
Если опоздание более двух недель, задание не проверяется.

## Ведомость с оценками
Ткнуть [сюда]()

## Куда сдавать задания и в какие сроки

[HW1](https://github.com/pileyan/DPO_Python_2023/blob/master/homework/hw1.ipynb) сдавать [сюда](https://www.dropbox.com/request/cFiE1T0ucmnrbn57AxBe) (Сдавать до 25.02.2023 включительно)

[HW2]() сдавать [сюда]()

[HW3]() сдавать [сюда]()

[HW4] Парсинг информации

Найти некоторый сайт, где есть карточки: карточки товаров, карточки услуг, карточки предложений. 

Достать какую-то информацию с этих карточек, причем необходимо понимать, какую конкретно часть информации вы достали, сохранить информацию для последующего анализа. Собранный набор данных должен быть достаточно большим.

Примеры: 
 
а) достать отзывы на молочные продукты по состоянию на "вчера" с сайта Ленты. 
б) достать комментарии к чему-нибудь в ВК от разных людей (неплохо в качестве признаков использовать то, какие люди оставляют комментарии (пол/возраст/город/кол-во друзей/и тд)
в) достать описание карточек товаров с сайта типа "ЕАПТЕКА" вместе с составами препаратов, ценой, объемом упаковки и тд

То есть ЛЮБАЯ информация , в дальнейшем пригодная для анализа. Если вы не уверены в выбранной теме, напишите мне :)

Срок – до конца 23 октября :)

[HW5] Бот. Сдавать мне в ТГ, до конца курса

[HW6] Решить 40 задачек по SQL, сдавать мне в ТГ, до конца курса

[HW7] еще не выдал, но там будут Numpy и Pandas


## Как работать с Github?
Для скачивания файлов с Github необязательно иметь аккаунт, достаточно кликнуть на зеленую кнопку Clone or download в правом верхнем углу, выбрать Download ZIP и распаковать архив. В папке DPO_2020_autumn будут все файлы, загруженные на Github на момент скачивания.

Если файл .ipynb сохраняется как текст или с лишним расширением (например, .txt), то нужно выбрать при сохранении тип файла все файлы, 
а не текст, или после сохранения убрать вручную расширение, переименовав файл.

Подробнее про работу с GitHub через клиента можно прочитать [здесь]()

А еще очень рекомендую посмотреть [вот эту ссылку](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)
Здесь в одной статье рассказана бОльшая часть того, что нужно знать про Git.

## Формулировка задания про бота выдается сразу. Она приведена ниже:

Реализовать телеграм-бота для предоставления пользователю некоторой информации из интернета (под капотом лежит парсер). У бота должны быть: набор команд, с помощью которых он отвечает на вопрос пользователя (например, сколько стоит билет на оперу/балет в большом театре на указанную дату на указанные места или какова средняя указанная зарплата на позициях из указанного номера страницы поисковой выдачи на сайте headhunter по запросу ‘аналитик данных’, каков курс доллара на вчера, сегодня, три месяца назад и тд). Обязательные условия:

1) Не должно быть сообщений, на которые бот отвечает неадекватно ( у бота есть какая-то линия его взаимодействия с пользователем, если человек вводит какие-то данные неправильно, бот должен об этом сказать, если бот ответил на запрос клиента, программа должна выдать этот ответ и дать пользователю инструкции о том, как произвести новый запрос.) 
2) Должны быть команда с описанием функциональности бота и команда с описанием набора команд (веселая тавтология) , которые бот принимает.
3) бот должен на какой-то из запросов отправлять картиночки и/или смайлики/стикеры/видео
4) под капотом у бота обязательно должен быть парсер какой-то интернет ниформации (чтобы не было “узнать у пользователя его запрос - думать 5 минут - вывести число 42”

В идеале бот должен содержать взаимодействие с базой данных, например, если у вашего бота есть какой-то набор стадий взаимодействия с пользователем, база может хранить состояние последнего запроса пользователя, чтобы каждый вход в бота не обнулял историю (если это имеет смысл) например:

1) Я спрашивал у бота погоду в Усть-Ордынске, но не сказал за какой день
2) Бот запомнил, что я спрашивал про Усть-Ордынск и в момент моего следующего взаимодействия, скажем, через час, бот спросит: "Помню, вы хотели узнать про погоду в Усть-Ордынске, хотите уточнить день?"

ОЦЕНИВАНИЕ:
Реализация парсера - 5 баллов (вы выбрали тему вашего проекта (что будете искать?) и сделали парсер, который принимает ввод от пользователя в блокноте через input, обрабатывает ошибки в запросе и возвращает ответ).  Если вы используете принципиально другую штуку(не парсер): работу с картами, графами, координатами и т.д. Это будет оцениваться отдельно, но в минусе точно не окажетесь.


Дополнительные баллы: у вас сложный поисковый запрос с использованием Selenium или api, с которым пришлось повозиться (+ 1-2 балла)
Ваш парсер реализован внутри телеграм-бота. Бот умеет искать информацию по запросу и обрабатывать ошибку запроса. Бот умеет отвечать только на один запрос (например, выдача заболевших коронавирусом в определенной стране за вчерашний день). + 5 баллов


Опционально aka НЕ ОБЯЗАТЕЛЬНО:
1) Бота можно запустить на сервере heroku (или вашем собственном сервере, если такой имеется, или еще на каком-то хостинге) - тогда вам самим не придется держать программу включенной постоянно www.heroku.com + 2 доп. балла
2) Бот имеет расширенный функционал (уточнение запроса, агрегирование информации и т.д.) + 2 балла
2) Можно научить бота рисовать какие-то графики ( например статистику курса доллара относительно рубля за месяц) и отправлять их вам (картинки мы отправлять умеем, а графики рисовать очень просто: можно собрать интересующие данные в pandas-dataframe и воспользоваться встроенными методами визуализации) + 2 балла

Ни в чем себя не ограничивайте.
развесовка баллов дана, чтобы с помощью крутого бота вы могли компенсировать недоделанные задания 🙂

**Кто очень хочет, может приступать**

Бот вообще не обязан быть таким, как описано выше, если вы собираетесь для него применить что-то принципиально отличающееся от разобранного на курсе, например однажды мне выслали бота, который примерно высчитывал время, за которое человек пешком/на машине доберется из места с конкретными координатами до некоторого другого выбранного места, скажем, ресторана. Карта Москвы при этом представляется в виде графа и время считается по кратчайшему пути прохода этого графа, загруженность дорог можно учитывать с помощью учета разных весов на ребрах: больше вес – сильнее загружена дорога, такую информацию можно попытаться достать из интернетов, но , как вы понимаете, решение точно не самое тривиальное.

**Ни в чем себя не ограничивайте.**

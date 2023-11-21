# Python разработчик

## Ключевые компетенции
1. Python 3
2. ООП
3. Регулярные выражения
4. unittest
5. Django
6. Django Rest Framework
7. PostgreSQL
8. Redis
9. Celery
10. Git
11. Docker
12. aiogram
13. Linux
14. FastAPI
15. Pydantic
16. DDD
17. SQLAlchemy
18. Tortoise ORM
19. Grafana
20. pyTest
21. MongoDB
22. Pandas
23. Selenium

### Дополнительно:
1. HTML
2. CSS
3. JS
4. TypeScript
5. React JS
6. Redux
7. Webpack

### Инструменты:
1. Pycharm
2. GitHub 
3. GitLab 
4. dbdiagram 
5. PgAdmin 4 
6. Jira 
7. Trello
8. Редактор vim (nvim)
9. Miro

## Опыт работы

#### 1. <b>Стажировка в Clovery на позиции FullStack разработчика.</b>
 - Стек: Python/Django + DRF, React JS 
С помощью AJAX и DRF настраиваю взаимодействие Frontend и Backend. 
 - Освоил работу с Git в команде 
 - Занимался проектированием логики сервиса на miro
 - Занимался проектированием базы данных на dbdiagram
 - Настраивал логгирование в файлы. Помимо встроенного в Django, в некоторых местах воспользовался модулем logging.
 - В процессе работы минимально освоил регулярные выражения и применил их в некоторых местах
 - Познакомился с принципами программирования SOLID применил полученные знания в проекте
 - Освоил работу с инструментом Jira
 - Парсил данные для базы городов из википедии с помощью модуля beautifulsoup
 - Настраивал отправку почтовых писем регистрации и изменения пароля
 - Покрыл большую часть API unit тестами
 - Разобрался с принципами DDD и начал внедрять их в проект
 - Научился работать с сервером, разобрался с Nginx, gunicorn и daphne

#### Описание работы над проектом
После успешного окончания стажировки проект плавно перешел в стартап, 
который активно продвигается инвесторами. Недавно на сервис запустили первых людей.

Помимо бэкенда я написал большую часть фронтенд функционала, 
разобрался в TypeScript и начал внедрять его в проект.

Так же немного разобрался в настройке и разворачивании проекта на сервере,
научился работать с vim, писал bash-скрипты. Настраивал конфиги nginx.

Весь Backend на проекте полностью написан мной, по коду можно судить о навыках, 
которые были применены, в полном объеме.
Ссылка на демонстрационный репозиторий проекта: https://github.com/pten4uk99/Lectonic

#### 2. Курсы SkillFactory FullStack Developer.
- Стек: Python/Django, React JS. <br/>
В рамках обучения:
- Писал telegram бота на python
- Изучил ООП
- Запускал периодические задачи на Celery
- Немного затронул алгоритмы и структуры данных
- Приобрел навыки работы с HTML, CSS, JS, React JS и AJAX
- Настраивал PostgreSQL и Redis
- Работал с Docker. Запускал PostgreSQL и Redis в Docker контейнере
- На базовом уровне научился работать с терминалом Linux

#### 3.  Телеграм бот.
- Стек: aiogram, postgresql, pullenti. <br>
- Разобрался с библиотекой aiogram.
- В целях более глубокого понимания SQL и баз данных, 
было принято решение писать собственную ORM систему временно на SQLLite3, 
но в скором времени будет сделан переход на PostgreSQL.
- Улучшил свои наработки по архитектуре проекта 
и активно применяю SOLID принципы.
- Разобрался с библиотекой pullenti и с тем, как происходит анализ текста.

<br> Ссылка на репозиторий проекта: https://github.com/pten4uk99/admission-bot

#### 4.  CRM система для салона красоты.
- Стек: FastAPI, SQLAlchemy, ReactJS
- Разобрался в основах работы фреймворка FastAPI
- Освоил работу с орм системой SQLAlchemy
- Познакомился с библиотекой pydantic
- Изучил и применил на практике принципы 
предметно ориентированного программирования

Ссылка на демонстрационный репозиторий проекта: https://github.com/pten4uk99/CRM

#### 5.  Сервис для общения пользователей и администраторов через телеграм.
- Стек: FastAPI, Tortoise ORM, aiogram
- Разобрался с Tortoise ORM
- Улучшил понимание асинхронности в python
- Деплоил проект на сервер, настраивал nginx с нуля
- Подключал ssl сертификат (настраивал https)
- Познакомился с системой мониторинга Grafana (Loki, Promtail, Prometheus)
- Всё приложение запускается через docker-compose
- Научился работать с .env файлами

#### Описание работы над проектом
Работа происходила с наставником. 
Цель проекта - подготовить меня к работе с созданием 
бэкенда для боевых проектов с нуля. В результате получился рабочий бэкенд,
покрытый тестами и задеплоенный на сервер.

Ссылка на демонстрационный репозиторий проекта: https://github.com/pten4uk99/tg-admin-panel


#### 6. Сервис для получения списка комментариев с переданной страницы Notion.
- Стек: asyncio, pydantic
- Углубился в асихнронность в python.

#### Описание работы над проектом
Заказ с фриланса. Была поставлена задача, иметь возможность получать 
все комментарии со страницы Notion и сохранять их в csv файл. 
Заказ был выполнен за 4 дня.

#### 7. Парсер данных из файлов в базу данных. 
- Стек: MongoDB, Pandas.
- Изучил процесс работы с MongoDB
- Оптимизировал загрузку данных в БД и парсинг больших файлов.

#### Описание работы над проектом
Заказ с фриланса. Заказчику требовалось написать консольное приложение, которое обрабатывало бы большие файлы (1-20ГБ) разных форматов (json, csv, xlsx, sql...), и собирало бы сырые данные из этих файлов в определенный формат, с определенными полями. В результате работы над проектом, было обработано и добавлено в базу более 40млн записей. 

#### 8. ГК Астра
В данный момент работаю в отделе автоматизации "Группы Компаний Астра". Пишу python скрипты и веб приложения, для автоматизации цикла разработки в компании. Активно работаю с FastAPI, асинхронным SQLAlchemy, React + Typescript + Redux, пишу End-To-End тесты на Selenium. Так же много взаимодействую с контейнеризацией и виртуализацией. Оптимизирую SQL запросы в базы данных, хранящих несколько миллионов записей. Написал сокет для передачи файлов между несколькими сервисами.

## В процессе изучения
В свободное время изучаю c++. 


## О себе
Практически 3 года опыта разработки на языке Python. Обладаю неплохой степенью перфекционизма, люблю когда все разложено по полочкам, без помойки (в коде стараюсь следовать тому же принципу). Если какая то задача меня зажигает, то могу с головой в нее погрузиться, пока не добьюсь результата, который мне нужен. 


## Контакты
Telegram: @pten4uk \
WhatsApp: +7 (926) 986-31-49

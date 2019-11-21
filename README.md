# General frontend FAQ

Платиновая шапка платинового треда.

### Об этом FAQ

Этот FAQ посвящен вкату во фронтенд-разработку. Данное вступление было составлено со слов уже опытных скриптовоенов для неуверенных в себе инфантилов. Прежде, чем задать очередной глупый вопрос — прочитай. Основное предназначение FAQ'a - дать краткое, но емкое направление по оптимальному изучению стэка технологий, которые используются во фронтенде.

FAQ составлялся уже довольно давно. За это время многие, причастные к его содержанию, успели вкатиться, жениться, выйти замуж, нарожать детей и стать добровольцами в межпланетной миссии Илона Маска. К сожалению, у текущего мейнтейнера (меня то бишь) совершенно нет времени в одиночку отслеживать появление новых учебных материалов и обновлять FAQ. Поэтому если у вас есть, чем поделиться - не стесняйтесь, шлите пулл реквесты. Это несложно.

Что мы ждем в пулл-реквесте:

- Какой-нибудь новый клевый бесплатный курс
- Не менее клевый и не менее новый, но платный курс
- Новая книжка, или старая, но не добавленная ранее в FAQ
- Новый положняк по фреймворкам/технологиям
- И все в таком духе

Чего мы `не` ждем в пулл-реквесте:

- Кулстори, как вы два года искали работу, проживая в ПГТ УстьЧеремушки (сочувствую, анон, но к FAQ это никак не относится)
- Холиварные утверждения уровня "жс завтра умрет, учите язык_нейм"
- И все в таком духе

Ждем ваших пул-реквестов!

## Содержание

1. [Интро](#Интро)
2. [Верстка](#Верстка)
3. [JavaScript](#javascript)
4. [Основы](#Основы)
5. [Продолжение](#Продолжение)
6. [Advanced](#advanced)
7. [Дополнительно](#Дополнительно)

## Интро

Фронтенд в 2019+ — это не:

- Верстка
- Клепание лендингов
- Фриланс на дядю Ваню за два доширака
- Колупание в вордпрессе, жумле и проприетарных конструкторах сайтов

B 2019 фронтенд-разработчик — это продвинутый формошлеп, который, в основном, копается в JS. Это не значит, что изучать верстку не обязательно — даже если на работе верстать не будете, на собеседовании обязательно спросят какую-нибудь фигню.

Что нужно знать на позицию фронтенд-разработчика начально-среднего уровня:

- HTML + CSS
- JS (ES6 как минимум, желательно шарить в TS / Flow)
- Фреймворк_нейм (лучший выбор для новичка все еще React).

Попутно изучается работа с командной строкой, git, инструменты сборки и прочие штуки. Все теоретические навыки обязательно подкрепляются практикой.

FAQ не освещает вопросы уровня:

> Можно ли вкатиться в `age` лет?

> Можно ли вкатиться без знаний программирования, матана, функционирования гипертекст протоколов и т.д.?

> Можно ли вкатиться без высшего образования или с дипломом заборостроительного ВУЗа?

> Есть ли работа?

На всякий случай - ответ на все подобные вопросы однозначный, `да`.

> Сколько времени займет обучение?

Много. В среднем, путь с нуля до уровня более-менее шарящего реактодебила/вьюдераста потребуется около года. Ключевое слово - `с нуля`.

> Могу ли учить верстку/JS после работы по 2 часа?

Можете, но это вряд ли будет эффективно.

> Слышал что для устройства на работу нужно портфолио

Мы тоже такое слышали, но обычно под "портфолио" понимают профиль на гитхабе и ссылочки на завершенные/активные проекты (если позволяет NDA | заказчик). В принципе, если не лень — можно даже простенький сайтецкий о себе забацать.

> Почему фронтенд вообще существует? Есть же CMS/конструкторы-сайтов.

Жизнь сложнее конструктора.

## Верстка

### Основы

#### Что нужно знать

- HTML:
  - Структура документа
  - Разметка
  - Тэги
  - Атрибуты
- CSS:

  - Основные селекторы (без фанатизма)
  - Основные свойства (отступы, размеры, цвет, шрифты и прочее)
  - Наследование свойств, каскад, вложенность
  - Основы сетки: блочная модель, флоаты, инлайн-блоки
  - Свойства position

- Все вместе:
  - Типовая разметка текста
  - Картиночки, ссылочки
  - Таблички, списочки
  - Формы, инпуты, лэйблы

#### Итого

Умение сверстать простенькую статику, без новомодных фич, без семантики, модульности, бэмов, шмэмов, респонсивности и прочего. На все про все около месяца.

#### Где учить, что читать

- Старт: интерактивные курсы хтмл академии: https://htmlacademy.ru/program бесплатных вполне хватит, но можно и оплатить подписку (лучше не надо). Можно спросить в треде скриншоты теории продвинутых интерактивов: их регулярно трут отовсюду, кроме меги, поэтому приходится перезаливать.
- http://htmlbook.ru/
- https://html5book.ru/
- https://webref.ru/
- Базовый интенсив все той же академии (брать на торрентах)

Не стоит увлекаться просмотром сотен тысяч курсов, вебинаров, туториалов и прочему. Как правило хтмл академии + хтмлбука более, чем достаточно для усвоения азов верстки.

#### Очень подробный верстка-гайдлайн

Стоит как минимум бегло просмотреть и прикинуть, что к чему: http://webmasters.teamdev.com/

---

### Верстка advanced

#### Что нужно знать

- HTML5: тэги и их семантику, атрибуты
- CSS:

  - Продвинутые селекторы (опять же без фанатизма, но знать полезно)
  - Градиенты, трансформации, анимации, переходы и прочие приколюхи
  - Флексы, гриды
  - Респонсив ("адаптивность")
  - Любой CSS фреймворк (bootstrap / foundation)

- Тулинг:

  - Автоматизация (галп, нпм, скрипты, можно уже даже потрогать вебпак)
  - Организация структуры проекта
  - Препроцессоры (любой на выбор)
  - Какой-нибудь template engine (pug, как один из самых популярных)
  - Работа в терминале (да, анон, удаляй свой github desktop, вот прямо сейчас)

- Не помешает:
  - Умение самостоятельно размечать и реализовывать динамические штуки (слайдер, например), подрубать и настраивать готовые плагинчики
  - Примерное понимание как работает js

На все про все: еще месяц-два-три в худшем случае.

#### Итого получаем

Готовую личинку верстальщика, которая сможет заверстать статику любой сложности по данному макету. Теоретически можно работать за дошираки, см [Дополнительно](#Дополнительно) (спойлер - на самом деле нельзя)

#### Где учить, что читать

`Важно: мы давно не следим за материалами, многое могло устареть. Есть что добавить? Шлите свои реквесты.`

- https://www.freecodecamp.org/ - бесплатный ресурс с туториалами по (HTML, CSS, JS, React, Angular, Bootstrap, Git, Linux) с подробными разъяснениями + бесплатные курсы с сертификатами. Подходит ко всему

- Интерактивные курсы хтмл академии https://htmlacademy.ru/program читаем про флексы, препроцессоры и т.п. Материалы платных интерактивов можно спросить в тредике
- http://nnmclub.to/forum/viewtopic.php?t=1220071 - 1 часть продвинутого курса от академии 2019. Там же можно найти 2 часть (заходим через VPN)
- http://htmlbook.ru/
- https://webref.ru/
- Верстка по БЭМ на примерах: http://habrahabr.ru/post/203440/
- http://ru.bem.info/ - документация БЭМ от Яндекса (ахтунг, фанатизм зашкаливает, не стоит увлекаться)
- http://getbootstrap.com/ - самый известный цсс-фреймворк.
- http://habrahabr.ru/post/114256/ - чеклист верстки. Несколько устарел, но, в целом, актуален.
- http://habrahabr.ru/hub/webdev/ - тематический хаб, иногда проскальзывают полезные публикации.
- Документация препроцессоров: http://sass-lang.com/ http://lesscss.org/ http://stylus-lang.com/

**Дополнительные ресурсы, которые могут быть полезными на данном этапе:**

- http://tympanus.net/codrops/ - еженедельная подборка новостей
- http://www.smashingmagazine.com/ - многое отсюда так или иначе переведено на русский, ресурс полезный для развития
- http://css-tricks.com/ - много готовых шаблонов для решения часто встречающихся задач
- http://codepen.io/ - ресурс с кучей интересных примеров кода
- http://www.html5rocks.com/en/ - туториалы от гугла
- http://frontender.info - неплохой ресурс, но редко обновляется
- http://www.sitepoint.com/html-css/, https://medium.com/tag/css, http://css-live.ru/ выборка статей по теме.
- http://nicothin.pro/page/console-windows
- http://nicothin.pro/page/kak-komfortno-rabotat-s-github-v-konsoli-windows
- Материалы интенсивов академии: https://github.com/tsergeytovarov/htmlacademy-basic-additional-material
- Материалы от teamtreehouse, любезно слитые аноном (англ): https://mega.nz/#!PgRiXJLK!Ske0xNBPaC9Rm_3mV9c5Zoz6rD5Yna-V7pI-yzJOB_A

> **А книги, книги то будут? Хочу книжку!**

Книги надо выбирать индивидуально. Если по HTML/CSS, то желательно, чтобы книга была не старше 2012 года, ну или хотя бы переиздана. Читай все что интересно. В любом случае это будет полезно.

- http://frontendbookshelf.ru/ - список полезных книг. Большинство актуальны, можно выбрать по языку, технологии и конкретному уровню знаний. Первооочередную литературу желательно брать оттуда.
- http://scanlibs.com/ что-то типа хранилища айти книг. Скачать книги можно бесплатно. Там есть дохуя всего. Если в свободном доступе не найдете, попробуйте поискать там.

#### Что верстать

- Макеты для верстки, тоже от академии. Все из их рассылки и не проверялось уже пару лет. https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
- Вполне годные макеты можно найти здесь: http://freebiesbug.com/psd-freebies/
- Moose - http://yadi.sk/d/g74XxFDUPyrob - корпоративный сайт
- Hotel - http://yadi.sk/d/5VEeZriDPyroK - туристический сайт
- Seabird - http://yadi.sk/d/XVt_w-TrPyrp4 - корпоративный сайт
- Appmo - https://yadi.sk/d/Ofaah1ZsTNrLf - лендинг приложения
- Cleanwhite - https://yadi.sk/d/b05MLaKITNrLy - корпоративный сайт
- Shoes - https://yadi.sk/d/Cp7qki0yTNrM4 - интернет-магазин обуви.
- Крупный пак с псдшками для практики - https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
- http://dbfreebies.co/templates http://freebiesbug.com/psd-freebies/website-template/ - cайты с макетами.
- http://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/ как работают браузеры.

#### В чем работать

В чем угодно. Универсальный выбор - Atom | VSCode, в них можно будет полноценно продолжать работать при переходе на жс+фреймворки. Для тех, у кого дрова вместо рабочей станции подойдет Sublime (на самом деле, тормозит не меньше атома). А вообще даже NP++ подойдет.

#### Что делать дальше

Сверстать пару макетов для закрепления и переходить к JS. Не помешает сразу зацепить гит, основные команды в терминале, поколупать какую-нибудь бубунту на виртуалке. Само собой использование галпа / вебпака, отсутствие боязни терминала, понимание того, как браузер рендерит страничку, как лучше подключать шрифты/стили/скрипты и т.п.

#### Гайд от анона по гитхабу

> http://randomfederation.github.io/

#### Еще один неплохой гайд по гитхабу (на русском)

> https://githowto.com/ru

**[⬆ К оглавлению](#Содержание)**

---

## JavaScript

Мир верстки был довольно дружелюбным и понятным. Мир JS — это особый мир особого программирования, где любая задача может иметь десятки решений, где существуют сотни и тысячи инструментов, библиотек и подводных камней. Добро пожаловать в ад.

![alt text](http://i.imgur.com/lKnOgq7.png "Welcome to hell")

Шутка. На самом деле, все довольно хорошо, и есть устоявшийся мейнстримовый набор:

- ES6+
- Фреймворк на выбор
- Инструменты для работы с ЦСС на выбор (препроцессоры + бэм, цсс модули, css-in-js, либо свои корпоративные велосипеды)
- Webpack / Rollup

Помните, что ньюфага никто (адекватный) не посадит, например, писать / править конфиги под SSR, поэтому учить наизуть webpack internals нинужно.

Годный список из over 9000 ссылок по современному javascript и веб-разработке
[Spellbook of Modern Web Dev](https://github.com/dexteryy/spellbook-of-modern-webdev)

![alt text](https://res.cloudinary.com/css-tricks/image/upload/c_scale,w_1000,f_auto,q_auto/v1517951537/js-mindmap_g5kmeq.jpg "JS-2018 short roadmap")

### Основы

Лучший учебник на JavaScript на русском языке — [Кантор](http://learn.javascript.ru/) . Ультраплатиновая ультрагоднота. У многих с нее пригорает, поэтому палим фишку: читаем про сам язык, скипаем особенности работы всякого дрянья в IE6, задачи делаем избирательно. И будем вам щастье. А еще лучше - читать англ.версию (см ниже)

`NOTE!`

[Английская версия](https://learn.javascript.info) поддерживается автором в более актуальном состоянии. Сразу дается ES6, убрано всякое говно мамонта, пугающее ньюфагов.

Кантора нужно разнообразить видосами и другими сайтами. Одна и та же вещь, объясненная много раз разными словами, становится понятнее:

- Канал [Code Dojo](https://www.youtube.com/channel/UCY10FZglXJ8RL3xB04VpykQ) Относительно неплохие видео по ЕС6+, хотя все это есть и у Кантора. Есть немного реакта, редакса и ангуляра
- [Codecademy intro](https://www.codecademy.com/learn/introduction-to-javascript) - бесплатное интро в жс
- [Coursehunters](https://coursehunters.net/course/ponimanie-prototipnogo-nasledovaniya-v-javascript) - скринкаст egghead, популярно и кратко о прототипах, всего 30 минут, ES6
- [Udemy](https://www.udemy.com/the-complete-javascript-course/) - неплохой платный курс (ну вы понели намек, да?)
- [Treehouse](https://teamtreehouse.com) и [Codeschool](https://www.codeschool.com) — тоже интерактивные курсы, платные.
- Канал [LearnCode.academy](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw) — Очень годный канал (англ). Смотреть ES5 и ES6.

Основной справочник по JS — [Mozilla Developer Network](http://developer.mozilla.org/en/docs/Web/JavaScript). Хотите почитать про промисы — пишите в гугле `promises mdn`.

---

## Продолжение

- Продолжаем читать Кантора: заканчиваем первую часть, читаем DOM, события. Материалы касательно работы с графикой можно опустить.
- Канал [Sorax](https://www.youtube.com/user/ArtSorax) очень клевый канал по "олдскульной ванилле" (ES5, прототипы и прочие прелести жизни). Алярм: может закипеть мозг, объясняет очень быстро и четко, никаких вам "переменная это коробочка с данными"
- [coursehunters/udemy](https://coursehunters.net/course/100-algoritmov-javascript) - интро в алгоритмы
- [Coursera](https://www.coursera.org/) Неплохой ресурс, но почти все платно, нуждающиеся могут поискать конкретные курсы на торрентах (они есть).
- [Codeschool](http://codeschool.com/) Аналогично
- [JS the Right Way](http://jstherightway.org/) Невообразимо объемный гайд: книги и статьи для изучения, описание фреймворков, стайлгайды и т.п. Рекомендуем ознакомиться
- [/r/ javascript](https://www.reddit.com/r/javascript/) Реддит, для любителей

> **А... книжки?**

Само собой. Ниже представлены только материалы со свободным лицензированием (бесплатные), их более, чем достаточно. Раздел давно не обновлялся, но почти все актуально до сих пор, и будет актуально еще долго. И да, почти все на английском, увы и ах.

### ES5

- [Выразительный JavaScript](http://eloquentjavascript.net/) - годнота, есть перевод и на русский, можно ограничиться только этой книгой
- [Speaking JavaScript](http://speakingjs.com/es5/)
- [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262/index.html)
- [JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)

### ES6

- [Exploring ES6](http://exploringjs.com/es2016-es2017/index.html/)
- [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/)

### Функциональный / асинхронный JS

- [Guide to functional programming](https://drboolean.gitbooks.io/mostly-adequate-guide/)
- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) Воистину легендарная книга
- [Краткий вольный пересказ You Don't Know JS](https://github.com/a-kon/ydkjs-synopsis) конспект YDKJS от одного очень шарящего анона

> Что уметь?

Писать рабочий, хорошо структурированный, модульный код ОБЯЗАТЕЛЬНО на ES6 (для этого придется потрогать вебпак + бабель). Для практики стоит придумать задачу - неважно, насколько шаблонной / скучной / избитой она будет. Легендарный тудулист вполне подойдет для оттачивания навыков: здесь вам и события, и работа с ДОМ, и обработка форм, можно прикрутить хранилище данных (localStorage, firebase) или даже "полноценный" бэкенд. К тому же, кода вполне достаточно для того, чтобы, например, написать приложение, используя MVC.

> Мой друг Самуил-Реактовец сказал, что прототипы не нужны. Можно их пропустить, уж очень они мудреные? Есть же ES6!

Нельзя. Во-первых, это один из самых часто встречающихся вопросов на собеседовании. Во-вторых, это основа основ JS, прототипы были, есть, будут и никуда не денутся, никакие ES6 классы и готовые либы этого не изменят. Понять прототипы === понять, как работает все, что на них завязано. А на них завязано вообще все. Ну, почти.

Все теоретические навыки обязательно подкрепляются практикой. Решайте задачки Кантора, каты на [CodeWars](https://www.codewars.com/?language=javascript). Попробуйте написать что-нибудь несложное, пусть код будет похож на императивную простыню: главное, чтобы работало.

---

## Advanced

### Промышленное программирование

Пришло время преодолеть разрыв между легкими и приятными учебными заданиями и суровой практикой с которой вам предстоит столкнуться на работе.

#### Выбор фреймворка

Первое и единственное решение, которое нужно принять: на какой фреймворк садиться. На текущий момент (2017) на выбор 2 с половиной стула:

##### Первый стул - [React](https://facebook.github.io/react/)

Традиционный выбор редакции 2015-2016-2017-2018(? время покажет)(upd: на середину 2018 года Реакт по прежнему универсальный выбор).
Ньюфажикам его советуют по многим причинам:

- JS центричность. Копаясь в Реакте вы невольно углубляетесь в понимание JS (на 2019 год это уже не так актуально)
- Относительно высокий, но "плоский" порог входа: придется изучить все, что так или иначе пригодится после (включая вебпак)
- Много вакансий
- Куча обучающих материалов
- Прекрасное коммьюнити

Минусы:

- Каждый пук надо прикручивать самостоятельно. Да, даже цсс, не говоря уж про роутер, стейтменеджмент и прочее
- Отдельный пункт - анальные боли при работе с формами (для чего есть сотни библиотек, каждая из которых имеет неповторимый набор багов)
- Фейсбук делает Реакт **под себя**, так что неудивляйтесь, если через 6 месяцев все придется переписывать
- Редакс все еще промышленный стандарт, со всеми вытекающими через одно место

> Но Реакт не фреймворк, мне так на курсах гикбрейнса сказали!

Есть строгий критерий, определяющий грань между фреймворком и кастомым кодом/библиотекой. Для тех, кому впадлу [читать](https://habrahabr.ru/post/116232/) - Реакт вполне себе фреймворк. Свои недовольства можете отправлять в спортлото.

##### Второй стул - [Vue 2](https://vuejs.org/)

Из плюсов:

- Полноценный набор инструментов - в отличие от Реакта не придется прикручивать гайками отваливающиеся цсс модули
- Предельная простота и интуитивность
- Прельстиво и приятно шлепать формы (а мы же здесь формошлепы, как никак)

Минусы:

- Эван почему-то считает своим долгом копипастить у Фейсбука все. Даже то, что нинужно
- Сильно меньше работы

##### Второй с половиной стул -[Angular](https://angular.io/)

Трудное дитя гугла, поимело провальный старт, из-за чего его считают плохим, негодным, что, на самом деле, не так.

Плюсы:

- Искаропки есть все. Т.е. вообще все. А то, чего нет, прикручивается через CLI
- Собственно, шедевральное CLI (начинася с 6 версии cdk)
- Коммьюнити из суровых энтерпрайзеров, которые видели некоторое shit и которых ничем не испугать
- Много работы

Минусы:

- Oche высокий порог входа, придется выучить вообще все, при чем не всегда понятно, в каком порядке.
- На этом, собственно, все

---

Это были стулья, а теперь **табуретки**:

- [AngularJS] - (не путать с Angular, который новый), он же ангулар первый — устарел морально, физически. Вакансии по-прежнему есть, в основном - поддержка дымящегося легаси. Учить просто так смысла нет. Да и вообще нет. Даже ссылочку вам не дадим, ха.
- [Backbone](http://backbonejs.org/) - good night, sweet prince. Можно поколупать, чтобы прикинуться олдэфагом. Но не нужно, вас все равно раскусят.
- [Inferno](https://infernojs.org/) - good night, sweet prince. Кговавый Фэйсбук купил разработчика, теперь он сидит в подвале без паспорта и пилит Реакт (тру стори);
- [Preact](https://preactjs.com/) - если видите в описании очередного фреймворка фразу 'this is fast lightwieght fork of React' - сразу закрывайте вкладку.
- [Aurelia](http://aurelia.io/) - заявлено, что это самый мощный, гибкий и современный (прямая цитата) JS фреймворк в мире, которым никто не пользуется. Ну вы поняли.
- [Mithril](http://mithril.js.org/) - позиционируется как супер-пупер альтернатива этим вашим реактам, ангуларам и вью. Но никем не используется. Такие дела.
- [Polymer](https://www.polymer-project.org/1.0/) - долгострой гугла, пишется конкурирующей с ангуларом командой. Даже где-то используется. Ходят слухи, что выйдет вместе с полноценным релизом нативных веб компонентов. А может и не выйдет.
- [Ember](http://emberjs.com/) - говорят, все, что придумали, уже давно было в Эмбере. Может так и есть, но эмбер даже на переписанном движке уж очень тормозной. Изредка мелькает в вакансиях (ищут спеца с опытом от 3 лет чисто на эмбере, что как бы намекает)
- [ExtJS](https://www.sencha.com/products/extjs/) - энтерпрайз монстр, который продается за 9к долларов и вертится где-то на задворках древних корпоративных ЦРМ и нигде больше не встречается.

Вышеперечисленные штуки указаны сугубо в ознакомительных целях.

---

Т.к. ваши покорные слуги - потомственные реактогоспода, то направление по изучению фреймворка дается именно на примере реакта, но вполне подойдет и для вью, и для ангулара.Лучшие ресурсы для начала обучения - официальная документация. Что у Реакта, что у Ангулара, что у Вью она очень подробная и человеческая.

1. Документация. Ваш самый лучший друг. Читаем, что вы собираетесь изучать, пробуем установить, трогаем примеры.
2. Курсы. Как правило, одного достаточно, смысла смотреть `n` курсов по одному и тому же предмету нет - все повторяется.
3. Видосики, записи конференций
4. Статьи, бест практис, опенсорс проекты
5. ...
6. ?
7. Profit!

Релейтед ресурсы:

- [Tutorial](https://reactjs.org/tutorial/tutorial.html) - официальный туториал
- [React Router](https://reacttraining.com/react-router/web/guides/philosophy) - хороший годный гайд-туториал-документация по реакт-роутеру.
- [Redux + react](https://redux.js.org/basics/usagewithreact) - официальный гайд по редаксу в связке с реактом.
- [React для начинающих](https://maxfarseer.gitbooks.io/react-course-ru-v2/content/) - обновленная версия уже давно протухшего туториала, пусть будет тут во имя исторической справедливости (можно посмотреть по фану)
- [React Redux](https://maxfarseer.gitbooks.io/redux-course-ru-v2/) - обновленный туториал по редаксу
- [React + Node.js + Bash](https://habr.com/ru/company/ruvds/blog/471040/) - Неплохой перевод туториала по реакту, ноду и башу. Оригинал на английском здесь (https://scrimba.com/playlist/p7P5Hd). Все бесплатно

Список из годных, просмотренных очень многими анонами и ютуб-каналов:

- Уже упомянутый канал [LearnCode.academy](https://www.youtube.com/watch?v=MhkGQAoc7bc&list=PLoYCgNOIyGABj2GQSlDRjgvXtqfDxKm5b) - хорошее, но краткое интро в реакт. Уже слегка (очень) устарело.
- Канал [Mindspace](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w) - Годнота от парня с забавным акцентом, более-менее актуально по сей день. Есть и Реакт, и А2, и немного Vue JS
- [Udemy](https://www.udemy.com/react-the-complete-guide-incl-redux/) - наверное самый годный курс по реакту. Можно найти на таррентах. Рекомендуем
- [Egghead](https://egghead.io/courses) прекрасный ресурс, где есть все. Много бесплатного, в том числе подробнейший скринкаст по редаксу от создателя редакса
- [IT-KAMASUTRA](https://www.youtube.com/channel/UCTW0FUhT0m-Bqg2trTbSs0g) - Различные видео по фронтенду (Js, React, Redux, Angular, Ajax, и другие полезные видео). Конечно интро музыка может быстро достать, мотайте сразу на +-20 сек начала видео

Кривая обучения в этом месте резко становится очень крутой и преодолеть ее с первого раза получается не у всех. Документация, случайные статьи и твиттеры разработчиков станут вашими новыми друзьями. И, конечно, эксперименты и практика.

#### Сборка

Если вы собирайтесь разбивать JS-код на несколько файлов и нормально использовать `import/export`, то вас настигнет вопрос сборки приложения. Сейчас для этого принято использовать [Webpack](https://webpack.js.org) — очень гибкий и мощный, но сложный в настройке инструмент, который интерпретирует все файлы как JS-модули.

[Скринкаст Кантора](https://www.youtube.com/playlist?list=PLDyvV36pndZHfBThhg4Z0822EEG9VGenn) поможет вам разобраться с базовой конфигурацией.
`Варнинг - скринкаст устарел, умер и разложился, оставим его здесь на память.`

[Полноценный скринкаст по новому вебпаку](https://www.youtube.com/playlist?list=PLTbz5Wv5vNcs0zKKmF0DSo6m05RnMqUXk) - must watch.

> По стостоянию на 21.12.2018 современные браузеры нативно поддерживают ES модули, что позволяет использовать `import/export'` прямо браузере, без вебпаков. Но на проде использовать пока рановато.

#### Расширение JS / Полезные инструменты

Если вы уже состояфшийся фронт и вам кажется, что развиваться больше некуда - вынуждены вас разочаровать.

- [TypeScript](https://www.typescriptlang.org/) - пожалуй, самый популярный и полезный яп, расширяющий возможности ванильного JS. Очень рекомендуем попробовать. Будем откровенны - если вы читаете этот раздел, то TS вы уже ДОЛЖНЫ знать, так что давайте, бегом-бегом читать документацию, благо она у ТС шикарная.
- [ClojureScript](https://clojurescript.org/) - кложура, которая транспайлится в ЖС.
- [elm](http://elm-lang.org/) - Функциональщина с приятным ароматом хаскеля и замечательным синтаксисом, от которого у неофитов выпадают глаза. До поры до времени активно форсился, но потом утратил позиции в связи с новым хайп-продуктом от господа бога нашего и пророка Фейсбука (о чем ниже).
- [ReasonML](https://reasonml.github.io/) - окамль с человеческим лицом от фейсбука. Ну или типа того, who cares? [Полезная ссылочка для инетерсующихся](http://2ality.com/2017/11/about-reasonml.html)
- [Dart](https://www.dartlang.org/) - авантюра гугла по созданию полноценной альтернативы JS со своим интерпретатором и андефайнедами. Попросили упомянуть - упомянули, вот. Есть такая штука, да, наверное, даже клевая (а может и нет). Больше сказать о нем нечего, в вакансиях почти не встречается, реального продакшн кода на нем лично составители FAQ и их знакомые не имели.
- [CoffeeScript](http://coffeescript.org/) - морально и физически устарел, все хорошее, что в нем было, перекочевало в ES6+. Иногда встречается в дремучих проектах, написанных на рубя с шаблонами. Учить не нужно, да и нечего там учить.
- [Flow](https://flow.org/en/docs/getting-started/) - костыль от фейсбука, призванный исправить фатальный недостаток (тм) жаваскрипта - слегка шизанутую утиную типизацию. Штука хорошая, но, к сожалению, проигрывает тайпскрипту в стабильности и готовности к продакшну (у автора полностью сломался конфиг при обновлении flow с 0.59 до 0.61). А еще у флоу ужасная, кошмарная, отвратительная докумнтация. Но попробовать стоит, займет всего пару дней.

TL;DR: берите TypeScript, не прогадаете. Все остальное (кроме кофе) можно потрогать на досуге, опять же - не прогадаете. Кофе не нужно, пейте чай. Шутка. Нет, правда, кофескрипт не нужен.

Не забываем про линтинг [ESLint](http://eslint.org) который избавит от совсем уж тупых ошибок/опечаток и приучит к написанию красивого кода.

Навыки работы с консолью и гитом подразумеваются для любого разработчика по умолчанию, об этом часто даже не пишут в вакансии.

### Устройство на работу

Причесываем гитхаб, маскируем коммиты уровня "ффыарфрырыффф". Составляем адекватное резюме, рассылаем его по всему хедхантеру, небо и Аллаха в копию. Впрочем, если в резюме видны зачатки мысли (и вы в ДС), то HR скоро вас сами найдут и обрушат лавину звонков и писем.

Основная часть собеседования это рассказ о себе и своих проектах. Заранее подумайте что сказать. Если есть ноутбук, то приходите с ним и показывайте проекты вживую.

#### Платиновые вопросы на собеседованиях

Большая часть из них разобрана здесь: [Вопросы кандидату на должность front-end разработчика](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/src/translations/russian)

Решения тестовых задач в функциональном стиле — очки х2: `спорный момент`. Инсайд: из-за наплыва "адептов функциональщины" и "детей ES6" могут потребовать написать "чистое решение" на ES5. Передаем привет всем, кто опустил / не понял прототипы.

**[⬆ К оглавлению](#Содержание)**

---

## Дополнительно

### Английский

> Нужен ли английский и как его выучить? Я и так уже по самую макушку завален материалами!

Нужен. Большая часть самых клевых материалов - на английском, большая часть влиятельных / шарящих людей в коммьюнити - не из СНГ и общаются на английском или своем родном (передаю привет одному голландцу). Плюс это нехилый бонус к трудоустройству.

Ниже будет подборка ответов / материалов по англйискому от анонов, за что им спасибо.

> Как учить?

Практикой и погружением:

- Приложения на смартфон Duolingo и Memrise. Первый бесплатен, второй платен, но бесплатной версии более чем достаточно. У Duolingo есть и [веб-версия](https://www.duolingo.com/)
- Чтение англоязычного интернета. Даже банальной Википедии будет достаточно. Еще можно читать газеты и издания мирового уровня типа:
- [vox](http://vox.com)
- [economist](http://www.economist.com/)
- [NYT](http://www.nytimes.com/)
- [BBC](http://www.bbc.com/)
- [spectrum](http://spectrum.ieee.org/)
- [combinator](https://news.ycombinator.com/)
- Фильмы на английском с сабами
- Игры на английском с сабами
- Интерфейс во всех приложениях на английском

Для грамматики подойдет курс от Полиглот 16 уроков. Еще стоит отметить простой переводчик по клику для хрома LinguaLeo. Другое полезное расширение - Grammarly, смотрит за правильностью того как ты пишешь на английском и высвечивает ошибки, неправильную грамматику, подсказывает правильный порядок слов и так далее. А ещё он может показывать значение слова по клику, с полноценной выдачей о значении этого слова.

Читать поначалу можно словарём - Chrome, Google Dictionary дополнение. Кликанье на все непонятные слова во время чтения/раздумья над смыслом статьи должно стать привычкой.

Обычно сначала трудно но через пару недель чувствуешь результат, потом уже стабильное улучшение.

### Подкасты

Подкасты сейчас очень популярны, только ленивый их не записывает. Но среди всей этой кучи встречаются реально интересные, где можно послушать крутых спецов из той или иной сферы или что-то полезное узнать. По фронтенду их существует огромное количество как на русском языке, так и на английском (в этом случае можно прокачать свой скилл восприятия английского на слух). Вот самые популярные из них.

На русском:
- [Веб-стандарты](https://soundcloud.com/web-standards)
- [FrontendWeekend](http://frontendweekend.ml/)
- [Фронтенд Юность](https://soundcloud.com/frontend_u)
- [DevShacht](https://soundcloud.com/devschacht)
- [Пятиминутка React](http://5minreact.ru/)

На ангийском:
- [Front End Happy Hour](https://frontendhappyhour.com/)
- [JS Party](https://changelog.com/jsparty)
- [JavaScript Jabber](https://devchat.tv/js-jabber/)
- [The Frontside Podcast](https://frontside.io/podcast/)
- [Egghead Podcasts](https://egghead.io/podcasts)


### Прочие мелочи

> Правда ли, что JS был придуман за 10 дней? Мой друг Вася-Джавист сказал, что это ущербный недоязык, хах.

Первая спецификация действительно была разработана и утверждена в кратчайшие сроки, и предназначалась для решения примитивнейших задач (оживить картинку, подсветить кнопочки). С тех пор прошло очень много времени, от первой спецификации осталась только общая концепция да парочка досадных багов, которые нельзя пофиксить из-за обратной совместимости (typeof Null, ага).

> Нужен ли матан?

Скажем так: лишним не будет, но и без него frontend разработчик не чувствует себя ущербным. Полезными будут знания дискретной математики, теории чисел и графов, а также основы теории алгоритмов (впрочем, это уже CS). Все это вполне изучается самостоятельно в свободное время. Для практики в этом деле лучше использовать Python: он более строгий, лаконичный и понятный. Хотя и на ES6 получаются очень даже красивые решения всяких олимпиадных задачек.

> Хочу фрилансить!

Фрилансить версталой - гиблое дело. Да и вообще фрилансить без опыта работы - гиблое дело. Да и вообще фрилансить в 2017 - гиблое дело. Адская конкуренция, кривые ТЗ, неадекватные заказчики, баны на апворках и прочие прелести ждут. Но никто не мешает попробовать.

> У вас тут все неправильно написано и вообще

FAQ полностью открыт для доработок и редактирования, присылайте свои pr или пишите в тредике, например. Обоснованные правки будут внесены.

> А где старая паста?

Вот же: http://pastebin.com/ytWW0UfU

> Нет-нет, где **та самая** старая паста?

Здесь: http://pastebin.com/tvvwC7uz

**[⬆ К оглавлению](#Содержание)**

## The Pereval server

### Программное обеспечение

- [OSINT](#OSINT)

  - [Анализ](#Анализ)

  - [Поиск](#Поиск)

- [Записи](#Записи)

  - [Базы знаний](#Базы_знаний)
  
  - [Текст](#Текст)

  - [Таблицы](#Таблицы)

  - [Схемы](#Схемы)

- [Архивирование](#Архивирование)

  - [Файлы](#Файлы)
  
  - [Веб-контент](#Веб-контент)

- [Централизация](#Централизация)

- [Коллаборация](#Коллаборация)

### OSINT

К сервисам для OSINT (Open source intelligence, разведка на основе открытых источников) отнесены веб-приложения, позволяющие искать информацию через API других сервисов, путём сканирования URL и IP, а также веб-приложения для анализа данных.

#### Анализ

- [CyberChef](https://github.com/gchq/CyberChef) ([демо](https://gchq.github.io/CyberChef/)) - визуальный редактор для анализа данных, созданный сотрудниками GCHQ — главной службы обеспечения информационной безопасности Великобритании. Позволяет обрабатывать и строки, и простым перетаскиванием открывать бинарные файлы, аналогично можно сохранять выходные данные.  Из операцияй доступны форматирование, шифрование, регулярные выражения, вычисление хешей, операции с публичным ключом и другое, все операции можно комбинировать.

#### Поиск

- [IVRE](https://github.com/cea-sec/ivre) ([офсайт](https://ivre.rocks/)) - фреймворк для разведки сетей, включает два модуля: один для пассивной (основанной на p0f или основанной на Bro) и второй для активной разведки (основывается на Nmap/ZMap). Возможен как запуск сканирования с клиентских/серверных машин, там и импорт готовых данных.

- [Spiderfoot](https://github.com/smicallef/spiderfoot) ([офсайт](http://www.spiderfoot.net/)) - сервис для автоматизации OSINT по многим направлениям: IP, DNS, почтовые ящики, базы ИБ. Поддерживается получение данных из более чем 50 источников. Доступна функциональность визуализации результатов.

- [Intrigue](https://github.com/intrigueio/intrigue-core) ([офсайт](https://intrigue.io/)) - удобный сервис для проведения выполнения различных задач в рамках разведки сетей и поиска. Полностью асинхронное выполнение заданий, сохранение всех результатов и их внутренняя линковка, визуализация.

- [Openwebspider](https://github.com/pereval-team/openwebspider) ([офсайт](http://www.openwebspider.org/), [демо](http://lab.openwebspider.org/)) - асинхронный краулер-индексатор страниц. Сохраняет проиндексированное текстовое содержимое, позволяя затем выполнять по нему поиск и просматривать связи между страницами.

### Записи

#### Базы знаний

- [dokuwiki](https://github.com/splitbrain/dokuwiki) ([офсайт](https://www.dokuwiki.org/), [демо](https://www.dokuwiki.org/)) - простой, но достаточно мощный вики-движок, который может быть использован для создания любой документации. Для хранения страниц используются текстовые файлы, а не база данных, что обеспечивает минимальные требования (только PHP) и поддержку любых кодировок. 

- [PmWiki](https://github.com/svn2github/pmwiki/tree/master/trunk) ([офсайт](http://www.pmwiki.org/), [демо](http://www.pmwiki.org/wiki/Main/WikiSandbox)) - минималистичный вики-движок, не использующий базу данных для хранения информации. Поддерживает полную кастомизируемость визуального интерфейса, почти полностью самогенерируема на основе шаблонов.

- [XWiki](https://github.com/xwiki/xwiki-platform) ([офсайт](http://www.xwiki.org/xwiki/bin/view/Main/WebHome), [демо](http://playground.xwiki.org/xwiki/bin/view/Main/WebHome)) - вики-сервис второго поколения, представляющий собой целую платформу для структуризации информации. Имеются визуальные редакторы и большое количество разнообразных расширений. 

#### Текст 

- [Hackpad](https://github.com/dropbox/hackpad) ([офсайт](https://hackpad.com/), [демо](https://hackpad.com/Hackpad-Media-Embed-Demo-oLn1PFq0H7P))

- [Paperwork](https://github.com/twostairs/paperwork) ([офсайт](http://paperwork.rocks/), [демо 1](https://oasis.sandstorm.io/appdemo/vxe8awcxvtj6yu0vgjpm1tsaeu7x8v8tfp71tyvnm6ykkephu9q0), [демо 2 - cloudron/cloudron](https://my-demo.cloudron.me/)) - сервис для хранения заметок, аналог Evernote, Microsoft OneNote, Google Keep.

- [CryptPad](https://github.com/xwiki-labs/cryptpad) ([офсайт](http://cryptpad.fr/), [демо](https://cryptpad.fr/pad/)) - сервис для хранения и совместного редактирования текста, программного кода, создание опросников, презентаций, досок для рисования. Возможно создавать ссылки только на просмотр. В основе используется технология блокчейна.

- [Etherpad](https://github.com/ether/etherpad-lite) ([офсайт](http://etherpad.org/), [демо](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60))

#### Таблицы

- [EtherCalc](https://github.com/audreyt/ethercalc) ([офсайт](https://ethercalc.net/), [демо](https://ethercalc.org/_new))

- [Ethersheet](https://github.com/ethersheet-collective/EtherSheet) ([офсайт](https://ethersheet.org/))

#### Схемы

- [Wisemapping](https://github.com/Rohja/wisemapping) ([офсайт](http://wisemapping.com/), [демо](https://app.wisemapping.com/c/maps/3/try)) - программа для построения майндкарт ([Mindmap](https://ru.wikipedia.org/wiki/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0_%D1%81%D0%B2%D1%8F%D0%B7%D0%B5%D0%B9)). Кроме прямых связей возможны ещё косвенные, поддерживаются изменение шрифта и цвета, иконки. Возможно создание ссылок на общий просмотр схемы.

### Архивирование

#### Файлы

- [Nextcloud](https://github.com/nextcloud/) ([офсайт](https://nextcloud.com/), [демо](https://demo.nextcloud.com/)) - актуальный полностью свободный форк популярного сервиса облачного хранения файлов ownCloud. 

#### Веб-контент

- [Webrecorder](https://github.com/webrecorder/webrecorder) ([офсайт](https://webrecorder.io/), [демо](https://webrecorder.io/)) - сервис для архивирования страниц со всем содержимым, поддерживающий перемещения по страницам и различные действия. За счёт использования отдельного сервера-прокси записываются все данные, проходящие через браузер. Доступен десктопный клиент для "воспроизведения" снимков.

- [wallabag](https://github.com/wallabag/wallabag) ([офсайт](https://wallabag.org/en), [демо - admin/pass](https://www.softaculous.com/softaculous/demos/wallabag)) - удобный сервис для сохранения страниц для последующего чтения. Контент полностью копируется в базе сервиса вместе со стилями и скриптами.

- [Bookmarks](https://github.com/devimust/easy-bookmark-manager) ([демо - admin/nimda](http://bookmarkdemo.miceli.click/)) - простой сервис для хранения закладок на страницы. Поддерживается система тегов с ранжированием, категории, импорт и экспорт.

### Централизация

- [pereval-dash](https://github.com/pereval-team/pereval-dash) ([оригинал](https://github.com/afaqurk/linux-dash)) - форк популярной веб-панели для мониторинга состояния сервера. Доступна простая кастомизируемость через редактирование/добавление шаблонов плиток с информацией и скриптов для её асинхронного получения.

- [OpenLDAP](https://github.com/openldap/openldap) ([офсайт](https://www.openldap.org/), [демо](http://demo.phpldapadmin.org/RELEASE/htdocs/index.php)) - для защиты доступа в большое количество сервисов так или иначе требуется единый реестр учётных записей. Опциональным средством в рамках Перевала может быть авторизация через LDAP, настраиваемая с помощью специального софта.

### Коллаборация

#### Средства общения

- [converse.js](https://github.com/jcbrand/converse.js) ([офсайт](https://conversejs.org/), [демо](https://conversejs.org/demo/)) - простой Jabber-клиент, который можно интегрировать в любую страницу. В качестве сервера можно использовать как свой, так и любой другой посторонний. [Пример настройки на русском](https://habrahabr.ru/post/249731/).

- [KiwiIRC](https://github.com/pereval-team/KiwiIRC) ([офсайт](https://kiwiirc.com/), [демо](https://kiwiirc.com/client))

#### Ведение задач

- [Wekan](https://github.com/wekan/wekan)

- [Restya](https://github.com/RestyaPlatform/board/)

- [Taskboard](https://github.com/kiswa/TaskBoard)

- [Kanboard](https://github.com/kanboard)


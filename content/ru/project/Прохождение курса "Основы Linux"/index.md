---
title: Курс "Основы Linux"
summary: Прохождение курса на платформе Stepik
  - Deep Learning
date: '2024-11-11T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Site
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Follow
    url: https://github.com/JaneZhibit
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# Цель работы

Прохождение курса "Основы Linux" на платформе Stepik


# Выполнение 

Здесь и далее представлены скриншоты, подтверждающие прохождение курса и демонстрирующие выполнение контрольных заданий

Чтобы узнать справку по команде, ознакомиться с принципами ее работы надо ввести man и название команды(рис. [-@fig:001]).

![1](image/1.jpeg){#fig:001 width=70%}

Для получения справки по командк ls надо ввести man ls
(рис. [-@fig:002]).

![2](image/2.jpeg){#fig:002 width=70%}


Введя pwd, пользователь получает путь до своего местоположения в каталогах(рис. [-@fig:003]).

![3](image/3.jpeg){#fig:003 width=70%}


Символ / нужен для обозначения начала пути файловой системы(рис. [-@fig:004]).

![4](image/4.jpeg){#fig:004 width=70%}


С помощью утилиты ls можно посмотреть списко всего содержимого директории. Другие варианты этим функцмоналом не обладают(рис. [-@fig:005]).

![5](image/5.jpeg){#fig:005 width=70%}


Параметр -а позволяет увидеть всю информацию, даже скрытых файлов(рис. [-@fig:006]).

![6](image/6.jpeg){#fig:006 width=70%}


Ключ -а позволяет увидеть всю информацию, даже скрытых файлов(рис. [-@fig:007]).

![7](image/7.jpeg){#fig:007 width=70%}


Ключ  -р или же parent позволяет создавать сразу вложенные директории(рис. [-@fig:008]).

![8](image/8.jpeg){#fig:008 width=70%}


Находясь внутри директории, чтобы она создалась раньше необходимо прописать чуть более подробный путь, также используя ключ р(рис. [-@fig:009]).

![9](image/9.jpeg){#fig:009 width=70%}


Утилита file используется для определения типа файлов. Остальные команды нужны для удаления и создания файлов, просмотра содержимого (рис. [-@fig:010]).

![10](image/10.jpeg){#fig:010 width=70%}

Утилита touch создает пустой файл, отсальные уоманды этим функционалом не обладают(рис. [-@fig:011]).

![11](image/11.jpeg){#fig:011 width=70%}

Команда rm удаляет файлы навсегда, восстановить их невозможно(рис. [-@fig:012]).

![12](image/12.jpeg){#fig:012 width=70%}


В данной ОС имена файлов зависят от регистра - файлы с маленькой и с большой буквы разные(рис. [-@fig:013]).

![13](image/13.jpeg){#fig:013 width=70%}


Ключ -r recursive необходим для выполнения копирования рекурсивно(рис. [-@fig:014]).

![14](image/14.jpeg){#fig:014 width=70%}


Для полного удаления используем rf - recirsive and force(рис. [-@fig:015]).

![15](image/15.jpeg){#fig:015 width=70%}


Вывести начальные строки позволяет комадна head. Это возможно сделать и по-другому, но с уточнениями(рис. [-@fig:016]).

![16](image/16.jpeg){#fig:016 width=70%}


Вывести конечные строки позволяет комадна head. Это возможно сделать и по-другому, но с более подробным синтаксисом(рис. [-@fig:017]).

![17](image/17.jpeg){#fig:017 width=70%}


Просматривать файлы, разделив их на страницы, можно командами more и less(рис. [-@fig:018]).

![18](image/18.jpeg){#fig:018 width=70%}


Вывод последних 2х строк возможен командой tail с ключом -2 и названием файла(рис. [-@fig:019]).

![19](image/19.jpeg){#fig:019 width=70%}


Для хранения своих персональных данных существует директория home(рис. [-@fig:020]).

![20](image/20.jpeg){#fig:020 width=70%}

Имена скрытых файлов всегда начинаются именно с символа точки(рис. [-@fig:021]).

![21](image/21.jpeg){#fig:021 width=70%}


Для съемных устройств точкой монтирования является директория media(рис. [-@fig:022]).

![22](image/22.jpeg){#fig:022 width=70%}


Файлы конфигурации хранятся в etc(рис. [-@fig:023]).

![23](image/23.jpeg){#fig:023 width=70%}


В свою очередь файлы устройства находятся в dev - device(рис. [-@fig:024]).

![24](image/24.jpeg){#fig:024 width=70%}


Центральное хранилище журналов - var/log(рис. [-@fig:025]).

![25](image/25.jpeg){#fig:025 width=70%}


Из представленных вариантов кэшированные данные приложений могут содержаться в var/cache(рис. [-@fig:026]).

![26](image/26.jpeg){#fig:026 width=70%}


Данна якоманда передает 4 аргумента -  4 пары одинарных кавычек(рис. [-@fig:027]).

![27](image/27.jpeg){#fig:027 width=70%}


Количество пробелов сохраниться только если передавать всю строку целиком, с помощью одинарных или двойных кавычек(рис. [-@fig:028]).

![28](image/28.jpeg){#fig:028 width=70%}


Определить данное различие команд можно с помощью type(рис. [-@fig:029]).

![29](image/29.jpeg){#fig:029 width=70%}


Для такого типа поиска используется команда which(рис. [-@fig:030]).

![30](image/30.jpeg){#fig:030 width=70%}


Чтобы создать псевдоним используем alias и соответсвенно название и команду(рис. [-@fig:031]).

![31](image/31.jpeg){#fig:031 width=70%}

Из перечисленных команд встроеннымиявляются - alias, echo. Остальные к ним не относятся(рис. [-@fig:032]).

![32](image/32.jpeg){#fig:032 width=70%}

Внешними являются все представленные команды кроме alias. Обратим внимание, что команда может одновременно относиться к обоим типам(рис. [-@fig:033]).

![33](image/33.jpeg){#fig:033 width=70%}

Рассмотримсоотношение бинарных файлов и директирий
alias - 

route - sbin

rm - bin

tac - usr/bin
(рис. [-@fig:034]).

![34](image/34.jpeg){#fig:034 width=70%}

Для последовательного выполнения команд, заданных одной строкой использюется знак ;(рис. [-@fig:035]).

![35](image/35.jpeg){#fig:035 width=70%}

При остутсствие необходимости ожидания заврешения работы  можно использовать &  и сразу ввводить новую команду(рис. [-@fig:036]).

![36](image/36.jpeg){#fig:036 width=70%}

Логическо и - &&

Логическо или - ||(рис. [-@fig:037]).

![37](image/37.jpeg){#fig:037 width=70%}

'#' - символ для последующего написания комментариев(рис. [-@fig:038]).

![38](image/38.jpeg){#fig:038 width=70%}

При необходимости вывод символа без его свойств используется обратный слэш - \(рис. [-@fig:039]).

![39](image/39.jpeg){#fig:039 width=70%}



Узнать текущее местоположение и содержимое кталога можно введя  pwd; ls(рис. [-@fig:040]).

![40](image/40.jpeg){#fig:040 width=70%}

Данная строка удаляет файл и сообщает, успешно или нет выполнена команда(рис. [-@fig:041]).

![41](image/41.jpeg){#fig:041 width=70%}



Переменные в оболочке обозначаются символом доллара $(рис. [-@fig:042]).

![42](image/42.jpeg){#fig:042 width=70%}



Присвоение значения происходит так: $Имя=Значение. Обратим внимание, на отсутствие пробелов(рис. [-@fig:043]).

![43](image/43.jpeg){#fig:043 width=70%}



Список переменных можно увидеть с помощью команд set и env(рис. [-@fig:044]).

![44](image/44.jpeg){#fig:044 width=70%}



В выводе название переменной указано в кавычках, следовательно результатом будет просто название, а не значение(рис. [-@fig:045]).

![45](image/45.jpeg){#fig:045 width=70%}



Здесь используются двойные кавычки, что дает компьютеру понять, что вывести надо значение переменной(рис. [-@fig:046]).

![46](image/46.jpeg){#fig:046 width=70%}



Для удаления переменной окружения использутеся unset(рис. [-@fig:047]).

![47](image/47.jpeg){#fig:047 width=70%}


Это делает переменная $PATH(рис. [-@fig:048]).

![48](image/48.jpeg){#fig:048 width=70%}



Данное действие осуществить с помощью доллара и скобок или же одинарных кавычек(рис. [-@fig:049]).

![49](image/49.jpeg){#fig:049 width=70%}


Многоуровневое встраиване делается за счет символа доллара и кавычек(рис. [-@fig:050]).

![50](image/50.jpeg){#fig:050 width=70%}


На скриншоте видно правильное соотношеие(рис. [-@fig:051]).

![51](image/51.jpeg){#fig:051 width=70%}


Пробел позволяет не сохранять команду в истории(рис. [-@fig:052]).

![52](image/52.jpeg){#fig:052 width=70%}


Сохранить определнное количество команд в истории возможно указав размер командой HISTSIZE(рис. [-@fig:053]).

![53](image/53.jpeg){#fig:053 width=70%}


Соотношение потоков ввода-вывода и номеров представлено ниже(рис. [-@fig:054]).

![54](image/54.jpeg){#fig:054 width=70%}


Содержимое будет удалено при использовании > (рис. [-@fig:055]).

![55](image/55.jpeg){#fig:055 width=70%}


Сообщение не будет выводиться при перенаправлении потоков - в 1м и последнем случаях(рис. [-@fig:056]).

![56](image/56.jpeg){#fig:056 width=70%}


Активирование режима происходит командами set -o noclobber и  set -C(рис. [-@fig:057]).

![57](image/57.jpeg){#fig:057 width=70%}


Да, параметр активирован, перезапись предотвращается(рис. [-@fig:058]).

![58](image/58.jpeg){#fig:058 width=70%}


Два вывода имеется только у командаы tee(рис. [-@fig:059]).

![59](image/59.jpeg){#fig:059 width=70%}



Команды и их функционал представлены на скриншоте (рис. [-@fig:060]).

![60](image/60.jpeg){#fig:060 width=70%}


В пропуск, для подсчета строк, необходимо добавть wc(рис. [-@fig:061]).

![61](image/61.jpeg){#fig:061 width=70%}


Для сортировки по второму столбцу используем ключ -k 2(рис. [-@fig:062]).

![62](image/62.jpeg){#fig:062 width=70%}


На скриншоте показано праавильное соотношение команд и того, для чего и когда они применяются(рис. [-@fig:063]).

![63](image/63.jpeg){#fig:063 width=70%}


Для того, чтобы созданный файл можно было найти с помощью locate необходимо обновить базу данных - updatedb(рис. [-@fig:064]).

![64](image/64.jpeg){#fig:064 width=70%}


Найти все директории можно ключом -d. Также необходимо указать сам шаблон для поиска - "foo" (рис. [-@fig:065]).

![65](image/65.jpeg){#fig:065 width=70%}


Поиск файлов рсуществялется с помощью указания f  и шаблона '*bar'(рис. [-@fig:066]).

![66](image/66.jpeg){#fig:066 width=70%}


Для поиска и копирования файлов введем катаолг /etc, шаблон файлов и пропишем копирование(рис. [-@fig:067]).

![67](image/67.jpeg){#fig:067 width=70%}


На скриншоте представлено соответсвие сокращений с их расшифровками(рис. [-@fig:068]).

![68](image/68.jpeg){#fig:068 width=70%}


При таком выводе могли использоваться только 2 и 6 команды с ключом G и E и таким синтаксисом(рис. [-@fig:069]).

![69](image/69.jpeg){#fig:069 width=70%}


Из Бельгии найти спортсменов можно используя ключ -i, то есть не учитывая регистр(рис. [-@fig:070]).

![70](image/70.jpeg){#fig:070 width=70%}




Правильное соотношение маски с выводом представлено ниже(рис. [-@fig:071]).

![71](image/71.jpeg){#fig:071 width=70%}

Данный вывод возможен только при вводе команд 2 и 6 - обязательно не учитывается регистр и соответсвующий синтаксис(рис. [-@fig:072]).

![72](image/72.jpeg){#fig:072 width=70%}



Здесь  происходит замена "За" на "При", получается Приморский(рис. [-@fig:073]).

![73](image/73.jpeg){#fig:073 width=70%}



В следующем примере заменилось "Заморский" на "Заморить", следовательно заменили "ский" на "ить"(рис. [-@fig:074]).

![74](image/74.jpeg){#fig:074 width=70%}



В этом случае символы && дублирует текст перед этим - получается послепослезавтра (рис. [-@fig:075]).

![75](image/75.jpeg){#fig:075 width=70%}



Здесь происходит перестановка числа и месяца, также меняется символточки на слэш(рис. [-@fig:076]).

![76](image/76.jpeg){#fig:076 width=70%}



Клавиша esc предназначена для перевода редактора в режим ввода команд, а вот для ввода текста используется insert(рис. [-@fig:077]).

![77](image/77.jpeg){#fig:077 width=70%}



Перейти в режим ввода текста можно командами a, i, o(рис. [-@fig:078]).

![78](image/78.jpeg){#fig:078 width=70%}



w - write, сохранение, q - quit, завершение, также это можно сделать командой ZZ (рис. [-@fig:079]).

![79](image/79.jpeg){#fig:079 width=70%}


Соотношение команд и их функцинала представлено на скриншоте(рис. [-@fig:080]).

![80](image/80.jpeg){#fig:080 width=70%}



yyp - комбинация для создания дупликата строки(рис. [-@fig:081]).

![81](image/81.jpeg){#fig:081 width=70%}




Для смены строк местами необходимо использовать сочетание ddp(рис. [-@fig:082]).

![82](image/82.jpeg){#fig:082 width=70%}


Для выполнения этого действия надо сначала указать номера строк, затем где меняем и на что меняем(рис. [-@fig:083]).

![83](image/83.jpeg){#fig:083 width=70%}



she-bang - последовательность символом для запуска сценариев в оболочке(рис. [-@fig:084]).

![84](image/84.jpeg){#fig:084 width=70%}



Примеры she-bang должны включать в себя #! bin и оболочку - bash, csh и другие(рис. [-@fig:085]).

![85](image/85.jpeg){#fig:085 width=70%}



Для запуска в оболочке Korn shell необходимо написать ее сокращение - ksh(рис. [-@fig:086]).

![86](image/86.jpeg){#fig:086 width=70%}



На скриншоте прдеставлен написанный пример программы, читающей и выводящей различные переменные(рис. [-@fig:087]).

![87](image/87.jpeg){#fig:087 width=70%}



Команде test эквивалентны символы [] (рис. [-@fig:088]).

![88](image/88.jpeg){#fig:088 width=70%}



На скриншоте представлено верное соотношение синтаксиса команды с тем, что она делает(рис. [-@fig:089]).

![89](image/89.jpeg){#fig:089 width=70%}



Проанализировав представленный код, можно понять, что выводиться будет "мало" , так как выполнятеся условия else(11 меньше 42)(рис. [-@fig:090]).

![90](image/90.jpeg){#fig:090 width=70%}

При исполнении скрипта выводится 1: 4 - 3, так как выполняется первое условие(рис. [-@fig:091]).

![91](image/91.jpeg){#fig:091 width=70%}


Для последовательного вывода чисел необходимо просто прописать условие - 10..1(рис. [-@fig:092]).

![92](image/92.jpeg){#fig:092 width=70%}



Здесь также необходимо только прописать условие "пока i меньше или равно 11"(рис. [-@fig:093]).

![93](image/93.jpeg){#fig:093 width=70%}



Аналогично прописываем условия соотаетсвенно заданию - "пока не станет меньше 3"(рис. [-@fig:094]).

![94](image/94.jpeg){#fig:094 width=70%}



Напишем скрипт, считывающий переменные и выводяший сумму от a до  b(рис. [-@fig:095]).

![95](image/95.jpeg){#fig:095 width=70%}



На скриншоте представлено соотношение символа $ и доп символов с их обозначениями - номерами аргументов, их количеством и тд(рис. [-@fig:096]).

![96](image/96.jpeg){#fig:096 width=70%}


Для получения параметром сценариев существует спциальная функция  getopts(рис. [-@fig:097]).

![97](image/97.jpeg){#fig:097 width=70%}



В свою очередь параметры функционирования оболочки можно получить с  помощью shopt(рис. [-@fig:098]).

![98](image/98.jpeg){#fig:098 width=70%}



Последовательный вывод аргументов с предварительной проверкой аргументов осуществляется циклом while  и передачей туда аргументов(рис. [-@fig:099]).

![99](image/99.jpeg){#fig:099 width=70%}


Команда eval - evaluate позволяет интерпретировать аргументы в директивы сценария оболочки(рис. [-@fig:100]).

![100](image/100.jpeg){#fig:100 width=70%}

Наличие двойных скобок позволяет сравнивать числовые значения(рис. [-@fig:101]).
 
![101](image/101.jpeg){#fig:101 width=70%}



Вычисления значений в оболочке происходят командой let(рис. [-@fig:102]).

![102](image/102.jpeg){#fig:102 width=70%}


За имя учетной записи отвечает команда who am i(whoami), другие вариации невозможны(рис. [-@fig:103]).

![103](image/103.jpeg){#fig:103 width=70%}


Входящих в системы, напротив, можно узнать командами who и w(рис. [-@fig:104]).

![104](image/104.jpeg){#fig:104 width=70%}


id - утилита для подробной информации об идентификаторе, группах и тд пользователя(рис. [-@fig:105]).

![105](image/105.jpeg){#fig:105 width=70%}


Запуск оболочки от лица суперпользователя осуществялется командой su (рис. [-@fig:106]).

![106](image/106.jpeg){#fig:106 width=70%}


Команда по умолчанию не меняет переменные окружения оболочки(рис. [-@fig:107]).

![107](image/107.jpeg){#fig:107 width=70%}


Команда su - позволяет работать в окружении оболочки целевого пользователя, а не обязательно исходного, как по умолчанию(рис. [-@fig:108]).

![108](image/108.jpeg){#fig:108 width=70%}


Не зная пароля, но введя команду sudo, можно выполнить команду от имени другого пользователя(рис. [-@fig:109]).

![109](image/109.jpeg){#fig:109 width=70%}


По умолчанию пароль от root не задается, это можно сделать самостоятельно в настройках(рис. [-@fig:110]).

![110](image/110.jpeg){#fig:110 width=70%}

Вся локальная база даннных учетных записей нахоится в директории   passwd(рис. [-@fig:111]).

![111](image/111.jpeg){#fig:111 width=70%}

Больше всего полномочий иммет пользователь root или же суперпользователь(рис. [-@fig:112]).

![112](image/112.jpeg){#fig:112 width=70%}


На скриншоте представлено верное соотношения утилит и функций(рис. [-@fig:113]).

![113](image/113.jpeg){#fig:113 width=70%}


Директория skel - директория-шаблон домашней директории(рис. [-@fig:114]).

![114](image/114.jpeg){#fig:114 width=70%}


Именно в зашифрованном виде пароли хранятся в каталогу shadow(рис. [-@fig:115]).

![115](image/115.jpeg){#fig:115 width=70%}


Утилиты openssl и passwd позволяют шифровать фразу для создания пароля, друние утилиты для этого не подходят(рис. [-@fig:116]).

![116](image/116.jpeg){#fig:116 width=70%}


Данная утилита обладает большим функционалом, в частности она позволяет устанавливать различные даты и сроки действия паролей(рис. [-@fig:117]).

![117](image/117.jpeg){#fig:117 width=70%}


наличие ! перед кэшем свидельствует о блокировке записи (рис. [-@fig:118]).

![118](image/118.jpeg){#fig:118 width=70%}


Необходим файл, находящийся в каталоге etc(рис. [-@fig:119]).

![119](image/119.jpeg){#fig:119 width=70%}


В целом, подходят все представленные варианты(рис. [-@fig:120]).

![120](image/120.jpeg){#fig:120 width=70%}

Название утилиты gropadd указывает на то, что она создает новую группу(рис. [-@fig:121]).

![121](image/121.jpeg){#fig:121 width=70%}


Принадлежность пользователей к группам содержится в папке group(рис. [-@fig:122]).

![122](image/122.jpeg){#fig:122 width=70%}


Groups - команда, показывающая принадлежность пользователя к группам(рис. [-@fig:123]).

![123](image/123.jpeg){#fig:123 width=70%}


Usermod - команда, позволящая изменить членство пользователя. Остальные команды были рассмотрены ранее(groupmod - изменение имени)(рис. [-@fig:124]).

![124](image/124.jpeg){#fig:124 width=70%}


Для этого существует ключ а(рис. [-@fig:125]).

![125](image/125.jpeg){#fig:125 width=70%}


Groupmod - утилита для изменения названия, аналогична usermod(рис. [-@fig:126]).

![126](image/126.jpeg){#fig:126 width=70%}


А вот утилита chown позволяет менять и имя группы, и пользователя владеющими файлом(рис. [-@fig:127]).

![127](image/127.jpeg){#fig:127 width=70%}


Chgrp - изменение имени группы, владеющей файлом(рис. [-@fig:128]).

![128](image/128.jpeg){#fig:128 width=70%}


Утилита chmod  отвечает за права доступа к файлу(не путать с chown(рис. [-@fig:129]).

![129](image/129.jpeg){#fig:129 width=70%}


Заменить имя пользователя позволит команда chown с указанием на кого менять и каталога(рис. [-@fig:130]).

![130](image/130.jpeg){#fig:130 width=70%}


Для замены группы воспользуемся командой chgrp, остальное аналогичнопримеру выше(рис. [-@fig:131]).

![131](image/131.jpeg){#fig:131 width=70%}

Для замены и группы и владельца необходима команда chown и запись через двоеточие(рис. [-@fig:132]).

![132](image/132.jpeg){#fig:132 width=70%}

Соответсвие обозначений и расшифровки представлено ниже(рис. [-@fig:133]).

![133](image/133.jpeg){#fig:133 width=70%}

Ниже представлено сопоставление прав доступа и их сокращений(рис. [-@fig:134]).

![134](image/134.jpeg){#fig:134 width=70%}

Для каждого пользователя отведено по ___, соответственно владельцу доступны вход и чтение, остальным только доступ(рис. [-@fig:135]).

![135](image/135.jpeg){#fig:135 width=70%}

Основываясь на команде, можно понять, что у владельца есть право на все, его группа имеет право на чтение и исполнение, у остальных пользователей только чтение, также, по дальнейшей информации, видно, что это файл(рис. [-@fig:136]).

![136](image/136.jpeg){#fig:136 width=70%}

Основываясь на таблице соответствий легко перевести права в виде строки в численное значение - 755(рис. [-@fig:137]).

![137](image/137.jpeg){#fig:137 width=70%}

рис. [-@fig:138]).

![138](image/137.jpeg){#fig:138 width=70%}

Аналогично получим 740((рис. [-@fig:139]).

![139](image/139.jpeg){#fig:139 width=70%}



Переведем в двоичную систему - пропуск=ноль, буква=1(рис. [-@fig:140]).

![140](image/140.jpeg){#fig:140 width=70%}

Функция sticky заключается в предотвращении удаления файлов пользователей не владельцев(рис. [-@fig:141]).

![141](image/141.jpeg){#fig:141 width=70%}



Описание использование бита описано в последнем варианте(рис. [-@fig:142]).

![142](image/142.jpeg){#fig:142 width=70%}



Описание использование бита описано во втором варианте - используется для повышения прав(рис. [-@fig:143]).

![143](image/143.jpeg){#fig:143 width=70%}



Утилита getfacl позволяет читать списки контроля доступа, а вот модификации и запись осуществить не получится(рис. [-@fig:144]).

![144](image/144.jpeg){#fig:144 width=70%}



Зато следующая утилита как ра-таки позволяет выполнить все эти операции - запись, удаление и модификация(рис. [-@fig:145]).

![145](image/145.jpeg){#fig:145 width=70%}



Inode - сьруктура данных, содержащая метаданные файла(рис. [-@fig:146]).

![146](image/146.jpeg){#fig:146 width=70%}



ls -li  команда для просмотра идентификаторов структуры(рис. [-@fig:147]).

![147](image/147.jpeg){#fig:147 width=70%}



Жесткие ссылки ограничены своими разделами дисков, имеют те же права, что и файл и связаны с inode. Права доступа имеют значение,они также указывают на структуры inode и не могут указывать на файлы из других систем (рис. [-@fig:148]).

![148](image/148.jpeg){#fig:148 width=70%}



Симвоилческие ссылки противоположны жестким по своей сути(рис. [-@fig:149]).

![149](image/149.jpeg){#fig:149 width=70%}


Ниже представлено соотношение файлов в каталогах с их содержимым(рис. [-@fig:150]).

![150](image/150.jpeg){#fig:150 width=70%}


Ниже представлено верное соотношение утилит с их значением(рис. [-@fig:151]).

![151](image/151.jpeg){#fig:151 width=70%}


Завершение курса

К сожалению, в процессе выполнения курса пришлось столкнуться с проблемой невозможности получения баллов за некоторые задания в связи с настройками авторов, тем не менее пройдено 92% материала и выполнены все задания.

(рис. [-@fig:152]).

![152](image/152.jpeg){#fig:152 width=70%}














# Выводы

В отчете представлено прохождение курса "Основы Linux" на платформе Stepik. В ходе работы былы получены знания по работе с операционной системы, изучены различные тонкости и нюансы, написано несколько скриптов и выполнено определенное количество заданий



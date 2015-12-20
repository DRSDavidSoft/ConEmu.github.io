---
title: ConEmu | FAQ - Частые вопросы

description: Частые вопросы пользователей о работе с ConEmu

breadcrumbs:
 - url: TableOfContents.html#conemu
   title: ConEmu

otherlang:
   eng: /en/ConEmuFAQ.html
   rus: /ru/ConEmuFAQ.html
---

# Содержание

Частые вопросы пользователей о работе с ConEmu.

  * [О главном](#q-1-general)
    * [Q. Что делать, если нашли ошибку?](#q-1-1)
    * [Q. А как же ConMan , альтернативная консоль и пр.?](#q-1-2)
    * [Q. Для чего нужен сертификат ConEmu .cer (digital certificate)?](#q-1-3)
    * [Q. Как импортировать в корневые доверенные сертификаты?](#q-1-4)
    * [Q. What is an Apps key?](#q-1-5)
    * [Q. What is a Host key?](#q-1-6)
    * [Q. Отображаются не все символы (иероглифы, троеточие, копирайты, и др.)](#q-1-7)
    * [Q. Можно ли запустить во вкладке ConEmu графическое (GUI) приложение?](#q-1-8)
    * [Q. Как запустить приложение в новой владке ConEmu ?](#q-1-9)
    * [Q. Как использовать параметр '-new_console'?](#q-1-10)
    * [Q. Какие переменные окружения устанавливает ConEmu ?](#q-1-11)
    * [Q. Запущенная консольная программа ничего не выводит на экран.](#q-1-12)
    * [Q. Программа не работает в режиме «Long console output».](#q-1-13)
  * [Дистрибутив](#q-2-distr)
    * [Q. Зачем нужен инсталлятор « ConEmuSetup.*.exe »?](#q-2-1)
    * [Q. Для чего нужен файл ConEmuC.exe ( ConEmuC64 .exe)?](#q-2-2)
    * [Q. Для чего нужен Far-плагин ConEmu .dll ( ConEmu .x64.dll)?](#q-2-3)
    * [Q. Для чего нужен файл ConEmuHk .dll ( ConEmuHk64 .dll)](#q-2-4)
    * [Q. Для чего нужен файл ExtendedConsole .dll ( ExtendedConsole64 .dll)?](#q-2-5)
  * [Portable-версия](#q-3-portable)
    * [Q. Может ли ConEmu быть портабельным?](#q-3-1)
    * [Q. При попытке использования « ConEmu .xml» появляется ошибка «XML setting file can not be used!»](#q-3-2)
    * [Q. Может ли ConEmu делать портабельными запускаемые в нем консольные приложения?](#q-3-3)
  * [Обновление](#q-4-update)
    * [Q. Умеет ли ConEmu обновляться автоматически?](#q-4-1)
    * [Q. Какие возможности у автоматического обновления?](#q-4-2)
  * [x64 issues](#q-5-x64)
    * [Q. Зачем нужны файлы ConEmuC.exe, ConEmuCD.dll и ConEmuHk .dll в 64битных ОС?](#q-5-1)
    * [Q. Зачем нужны файлы ConEmuC64 .exe, ConEmuCD64.dll и ConEmuHk64 .dll в 32битной версии ConEmu ?](#q-5-2)
    * [Q. При запуске команд start, echo (и прочих команд cmd.exe) на 64битной ОС возникает ошибка вида "File not found. Cannot execute. start".](#q-5-3)
    * [Q. При попытке запуска (из Far Manager) возникает системная ошибка вида: «Ошибка при запуске приложения (0xc0000142). Для выхода из приложения нажмите кнопку "OK".»](#q-5-4)
    * [Q. Что происходит с переменными окружения в 64битных OS?](#q-5-5)
  * [Настройка](#q-6-settings)
    * [Q. Можно ли запустить ConEmu так, чтобы в нем сразу было открыто несколько вкладок: Far, CMD, PowerShell ?](#q-6-1)
    * [Q. Двоятся окна Far Manager.](#q-6-2)
    * [Q. Как настроить растровый шрифт?](#q-6-3)
    * [Q. Почему горизонтальные рамки отображаются пунктиром/прерывисто?](#q-6-4)
    * [Q. Как запустить несколько консолей в сетке 2x2](#q-6-5)
    * [Q. Как настроить запуск cmd.exe под Администратором из контекстного меню Проводника Windows](#q-6-6)
    * [Q. Как поименовать запускаемые табы при запуске из задачи {Task}](#q-6-7)
    * [Q. Как настроить Git Bash Here в ConEmu](#q-6-8)
    * [Q. Как экспортировать настройки ConEmu](#q-6-9)
    * [Q. Как прицепить открытое консольное окно в новый экземпляр ConEmu](#q-6-10)
    * [Q. Как удалить пункты из списка «Create new console»](#q-6-11)
  * [Far Manager](#q-7-far)
    * [Q. Почему не работают табы (вкладки)?](#q-7-1)
    * [Q. Почему не работает (плагин) Drag-n-Drop?](#q-7-2)
    * [Q. Как закрыть таб (редактор/вьювер/фар) мышкой?](#q-7-3)
    * [Q. В Far не передаются нажатия кнопок мышки, колесо.](#q-7-4)
    * [Q. Почему не работает плагин FarHints ?](#q-7-5)
    * [Q. В какой-то момент перестают работать табы, Drag-n-Drop,...](#q-7-6)
    * [Q. По щелчку правой кнопкой мышки не появляется контекстное меню для файла/папки.](#q-7-7)
    * [Q. По щелчку правой кнопкой мышки появляется графическое меню, а хочу текстовое.](#q-7-8)
  * [Windows Vista](#q-8-vista)
    * [Q. В Windows Vista не срабатывает комбинация Ctrl-Win-Alt-Space для показа RealConsole .](#q-8-1)
    * [Q. В Windows Vista зависают другие консольные процессы.](#q-8-2)
  * [Аварийные завершения](#q-9-crash)
    * [Q. При завершении консольной программы возникает ошибка вида: Access violation at address 6F78DE5B in module ' ConEmuHk .dll'. Read of address 0071004E](#q-9-1)
    * [Q. ConEmu или консольное приложение зависает при выходе?](#q-9-2)
    * [Q. Как создать дамп памяти приложения?](#q-9-3)
    * [Q. Как узнать ИД процесса (PID)](#q-9-4)
    * [Q. Как запустить Диспетчер задач Windows](#q-9-5)
    * [Q. Что означает: ConEmuC: CreateFile (CONOUT$) failed, ErrCode =0x00000005](#q-9-6)
  * [Unsorted](#q-10-unsorted)
    * [Q. Как сворачивать ConEmu в трей (в иконку рядом с часами)?](#q-10-1)
    * [Q. Зачем ConEmu меняет шрифт у реальной консоли?](#q-10-2)
    * [Q. Почему-то отображается только часть консоли; консоль отображается сдвинутой; не отображается вообще.](#q-10-3)
    * [Q. Почему исчезает окно быстрого поиска в панелях при переключении языка?](#q-10-4)
    * [Q. Почему нет кнопок мультиконсоли на панели инструментов?](#q-10-5)
    * [Q. Зависает (в заголовке ConEmu отображается '...Waiting for result (10 sec)') через некоторое время в FAR появляется меню плагинов (или вызывается какой-то другой плагин).](#q-10-6)
    * [Q. Почему не отображается 'Background image'?](#q-10-7)
    * [Q. Зачем нужно подтверждение 'Press Enter to close console...' отображаемое перед закрытием консоли после завершения всех программ в ней?](#q-10-8)
    * [Q. Как отключить 'Press Enter to close console...'?](#q-10-9)
    * [Q. Запускается FAR, плагин установлен, но все равно появляется 'Press Enter to close console...'?](#q-10-10)
    * [Q. Почему Shift-Enter в панелях запускает новое окно с реальной консолью, а не в новой вкладке?](#q-10-11)
    * [Q. Почему в консоли отображается прямоугольник (рамка) вместо курсора?](#q-10-12)
    * [Q. В табах отображаются квадратики (вместо иероглифов).](#q-10-13)
    * [Q. Для консоли ConEmu не всплывает перевод GoldenDict](#q-10-14)



## О главном  {#q-1-general}




#### Q. Что делать, если нашли ошибку?   {#q-1-1}


A. Сначала проверить, повторяется ли ошибка БЕЗ ConEmu, в 'чистом' FAR?
Если не повторяется - проверить последнюю версию ConEmu.
Качать здесь: [http://www.fosshub.com/ConEmu.html](http://www.fosshub.com/ConEmu.html)
Если ошибка не исправлена - создавайте [Issue с подробным описанием](Issues.html).




#### Q. А как же ConMan, альтернативная консоль и пр.?   {#q-1-2}


A. Все встроено в ConEmu, только лучше ;) Флажок 'MultiCon' должен быть включен. Более того, использование ConMan вместе с ConEmu НЕ РЕКОМЕНДУЕТСЯ. Новую консоль можно создать как шорткатом (Win-W по умолчанию), так и добавлением к выполняемой команде параметра -new_console. Можно закрыть или перезапустить текущую консоль (Win-~). Длинный вывод последней консольной команды/программы можно посмотреть через плагин в редакторе или просмотрщике (макрос на Ctrl-O). Переключение между консолями Win-Q. Переключение между консолями и окнами Ctrl-Tab.




#### Q. Для чего нужен сертификат ConEmu.cer (digital certificate)?   {#q-1-3}


A. Для проверки целостности исполняемых файлов ConEmu.


A. Windows SmartScreen блокирует запуск файлов (Installer) от "непроверенных издателей".


A. Если сертификат импортирован в корневые доверенные сертификаты (для пользователя, компьютера или домена) то при запуске ConEmu в режиме администратора (Vista & Win7) в запросе UAC вместо злобного окна с "непроверенным издателем" отображается нормальное имя программы и "проверенный издатель: ConEmu-Maximus5".


A. Если сертификат импортирован в корневые доверенные сертификаты антивирусы (например KIS) будут считать программу доверенной.




#### Q. Как импортировать в корневые доверенные сертификаты?   {#q-1-4}


A. В Vista+ можно просто 'запустить' файл сертификата и нажать кнопку 'Установить сертификат'.


A. Через MMC -> оснастка Certificates.


A. С помощью утилиты CertMgr из Windows SDK:

~~~
   "C:\Program Files\Microsoft SDKs\Windows\v7.0\Bin\CertMgr" -add -c ConEmu.cer -s root
~~~

A. Подробнее об импорте здесь: [Установка сертификата](Certificate.html)




#### Q. What is an Apps key?   {#q-1-5}


A. [AppsKey](AppsKey.html).




#### Q. What is a Host key?   {#q-1-6}


A. This is sort of «substitution» for key chosed by user. For example you may choose common modifier (from one or more Ctrl/Alt/Shift/Apps) for group of actions. Browse «Keys & Macro» page in the Settings dialog.




#### Q. Отображаются не все символы (иероглифы, троеточие, копирайты, и др.)   {#q-1-7}


A. По какой-то причине ConEmu не смог сменить шрифт у реальной консоли. Выберите пункт системного меню окна ConEmu 'Properties' и на закладке 'Шрифт' выберите TrueType шрифт.


A. В настройке (Settings-ConEmu.reg, параметр 'ConsoleFontName') указан НЕ юникодный или отсутсвующий шрифт для консоли.




#### Q. Можно ли запустить во вкладке ConEmu графическое (GUI) приложение?   {#q-1-8}


A. Да, некоторые GUI приложения можно. Например Putty, Notepad, и т.п.




#### Q. Как запустить приложение в новой владке ConEmu?   {#q-1-9}


A. Указать приложение в поле 'Create new console' окна подтверждения создания новой консоли. Это окно можно вызвать из системного меню ConEmu «New console...» или с клавиатуры (по умолчанию это Win-W или Win-Shift-W).


A. Новую вкладку можно открыть из уже запущенной вкладки (например, из Far) используя параметр запуска '-new_console'. Например: `putty.exe -new_console`.




#### Q. Как использовать параметр '-new_console'?   {#q-1-10}


A. В настройке ConEmu должен быть включен флажок «Inject ConEmuHk». После этого, если ConEmu видит в строке запуска приложения/команды параметр '-new_console' он убирается из строки запуска, а приложение/команда выполняется в новой вкладке ConEmu.


A. Можно использовать дополнительные опции запуска: `-new_console[:bh[N]caru[:user:pwd]]`

* `b` - Create background tab
* `h<height>` - пример, h0 - отключить буфер, h9999 - включить буфер в 9999 строк
* `n` - отключить 'Press Enter or Esc to close console'
* `c` - принудительно включить 'Press Enter or Esc to close console' (default)
* `a` - RunAs shell verb (as Admin on Vista+, login/password in Win2k and WinXP)
* `r` - Run as restricted user
* `u` - ConEmu choose user dialog
* `u:<user>:<pwd>` - specify user/pwd in args, MUST BE LAST OPTION

**Пример:** «`"%ConEmuBaseDir%\ConEmuC.exe" /c dir "-new_console:bh9999c" c:\ /s`». Примечание, при запуске из Far Manager «`"%ConEmuBaseDir%\ConEmuC.exe" /c `» вводить необязательно.


A. Для удобства использования в Far можно установить макрос на ShiftEnter (см. примеры в дистрибутиве).


A. Обратите также внимание на параметр `-cur_console:h[N]` которым можно управлять включением длинного вывода команд или приложений при запуске их из [Far Manager](ConEmuFAQ.html#q-7-far).




#### Q. Какие переменные окружения устанавливает ConEmu?   {#q-1-11}


A. Читайте wiki-страницу [ConEmu Environment](ConEmuEnvironment.html).




#### Q. Запущенная консольная программа ничего не выводит на экран.   {#q-1-12}

**Этот вопрос относится только к [консольным приложениям](ConsoleApplication.html)!**

A. Некоторые программы работают с альтернативным буфером консоли, например telnet.exe, запущенный без параметров. Историю можно посмотреть здесь: [Issue 65](http://github.com/Maximus5/conemu-old-issues/issues/65). Проблема исправлена в сборке 120504, должен быть включен флажок «Inject [ConEmuHk](ConEmuHk.html)». В предыдущих версиях ConEmu можно было отобразить (CtrlWinAltSpace) окно реальной консоли и временно поработать с ним.


A. В результате какого-то бага в ShellExecuteEx, на некоторых OS, консольный процесс запускался с некорректным дескриптором буфера вывода.
Для исправления ошибки должен быть включен флажок «Inject ConEmuHk». Если ошибка не исправляется - создайте новый
[Issue](Issues.html) с подробным описанием проблемы и приложите отладочный лог запускаемой программы:
«Settings -> Debug -> Shell and processes».




#### Q. Программа не работает в режиме «Long console output».   {#q-1-13}


A. Некоторые программы не умеют корректно работать с длинным консольным буфером. Например bview, Aurora, и т.п. Есть несколько вариантов решения:

* Открывать программу в новой вкладке ConEmu при отключенной прокрутке. Например: "bview.exe -new_console:h"
* Указать, что прокрутку включать не нужно. Например: "ac.exe -cur_console:h"
* Или можно вообще отключить 'Long console output' на вкладке 'Tabs' окна 'Settings', если длинный вывод команд вам вообще не нужен



## Дистрибутив  {#q-2-distr}




#### Q. Зачем нужен инсталлятор «`ConEmuSetup.*.exe`»?   {#q-2-1}


A. Использовать exe-инсталлятор рекомендуется на компьютерах с включенным UAC (Vista и выше) если вы хотите установить ConEmu в «Program Files».


A. Инсталлятор также содержит некоторые дополнительный файлы, например KeyEvents.exe.




#### Q. Для чего нужен файл ConEmuC.exe (ConEmuC64.exe)?   {#q-2-2}


A. Это 'консольная' часть ConEmu. Через него графическая оболочка получает всю информацию о консоли. Этот процесс управляет автоматическим увеличением высоты буфера консоли при запуске команд/приложений. При запуске 'новой' консоли (Shift-Enter в FAR) прицепляет ее к ConEmu.




#### Q. Для чего нужен Far-плагин ConEmu.dll (ConEmu.x64.dll)?   {#q-2-3}


A. Это модуль, обеспечивающий связь между Far Manager и ConEmu.

* Без него не работают некоторые расширенные возможности (табы, Drag'n'Drop, прогресс).
* Без него не включается TrueColor в Far 3.x.
* Без него не будут работать некоторые другие плагины (FarHints например).
* Показывает скрытую консоль с FAR-ом, если случилось несчастье и ConEmu упал.
* После детача консоли (Ctrl-Alt-Tab) запускает новый ConEmu для новой консоли.
* Необходим для работы с длинным буфером вывода консольных приложений.
* Для работы мышки в «far /w» (System\WindowMode=1).



#### Q. Для чего нужен файл ConEmuHk.dll (ConEmuHk64.dll)   {#q-2-4}


A. Это модуль, внедряемый в приложения, запускаемые в ConEmu. Необходим для реализации некоторых опций, а также исправляет многие проблемы, проявляющиеся как в ConEmu, так и без него.

* всплывание GUI-диалогов (без него они окажутся позади ConEmu);
* корректную работу в Far Manager GUI-EMenu (иначе оно не закрывается кликом мышки);
* обеспечивает работу флажков "No zone check", "Ascii sort...", "Hourglass if not responding";
* обеспечивает работу параметра "-new_console";
* лечит проблемы ShellExecute (когда вывод батников не всегда виден в консоли);
* лечит зависания chcp;
* обеспечивает мониторинг "Shell and processes";
* внедрение GUI приожений во вкладку ConEmu;
* ANSI X3.64 и расширение xterm 256 color;
* опция "Change prompt text cursor position with Left Click";
* а также других опций (как существующих так и будущих) которые требуют работу «внутри процесса».



#### Q. Для чего нужен файл ExtendedConsole.dll (ExtendedConsole64.dll)?   {#q-2-5}


A. Это поддержка расширенной консоли в Far 3.x, должен располагаться в каталоге с файлом ConEmuHk.dll. При его наличии и включении флажка «TrueMod support» в Far можно настроить любые TrueColor цвета и стили (bold/italic/underline).




## Portable-версия  {#q-3-portable}




#### Q. Может ли ConEmu быть портабельным?   {#q-3-1}


A. Да. Для включения портабельности настроек ConEmu достаточно создать *пустой* файл «ConEmu.xml» рядом с ConEmuC.exe или с ConEmu.exe. Создать файл можно после запуска ConEmu, что позволяет сохранить загруженные из реестра настройки в XML-файл.




#### Q. При попытке использования «ConEmu.xml» появляется ошибка «XML setting file can not be used!»   {#q-3-2}


A. Собственно, в полном тексте этой ошибки все написано. В реестре не зарегистрирован интерфейс IID_IXMLDOMDocument. Чтобы его не регистрировать, можно рядом с ConEmuC.exe или с ConEmu.exe положить файлы «msxml3.dll» и «msxml3r.dll». Файлы лучше брать из Windows XP - в них меньше зависимостей и они будут работать в Windows 2000.




#### Q. Может ли ConEmu делать портабельными запускаемые в нем консольные приложения?   {#q-3-3}


A. Этот функционал в стадии разработки, планируется полный перехват работы с реестром запускаемых в ConEmu приложений.




## Обновление  {#q-4-update}




#### Q. Умеет ли ConEmu обновляться автоматически?   {#q-4-1}


A. Да. ConEmu может проверять наличие новых версий при запуске, ежечасно или по запросу пользователя ([SystemMenu](SystemMenu.html) -> Help -> Check for updates).




#### Q. Какие возможности у автоматического обновления?   {#q-4-2}


A. Вы можете настроить обновление так, как вам хочется.

* Возможна работа через Proxy.
* Можно проверять наличие как «стабильных» так и «alpha» сборок.
* При обнаружении новой версии можно отображать запрос на загрузку, а можно загружать пакет (архив или инсталлятор) сразу.
* Если ConEmu был установлен через инсталлятор, то при совпадении пути установки с путем запущенного ConEmu.exe (или ConEmu64.exe) обновление производится через пакет «`ConEmuSetup.*.exe`».
* В других случаях обновление производится из 7-zip архива.
* Для обновления через архив на компьютере должен быть установлен архиватор ([7-Zip](http://www.7-zip.org/) или [WinRar](http://www.rarlab.com/)).
* По умолчанию пакеты скачиваются в %TEMP% и удаляются после установки.
* Но, вы можете указать любую папку, в которую нужно скачивать пакеты обновления. Их можно не удалять после установки.
* Команда установки выполняется из временного cmd-файла, выполяемого в папке с ConEmu.exe. cmd-файл создается в %TEMP%.
  * Команда инсталлятора по умолчанию: `"%1" /p:%3 /qr`. Запускает соответствующий (x86/x64) msi-пакет с ключом `/qr` (обновление «без вопросов»).
  * Команда архиватора по умолчанию: `<архиватор> x -y "%1"`. Вместо `<архиватор>` указывается полный путь к любому архиватору, поддерживающему распаковку 7-Zip архивов: [7zg.exe, 7z.exe](http://www.7-zip.org/), [Unrar.exe, WinRar.exe](http://www.rarlab.com/), и т.п.
* Запуск cmd-файла со скриптом обновления (если пользователь согласился на обновление) выполняется после закрытия окна ConEmu (закрытия всех вкладок).
* Перед запуском cmd-файла выполняется проверка отсутствия других открытых окон ConEmu.
* После успешного обновления вы можете выполнить любую команду или скрипт (через cmd.exe). Например, вы можете скопировать новые файлы в другие папки, если на вашем компьютере установлено несколько копий ConEmu. По умолчанию, в папке с ConEmu.exe создается файл ConEmuUpdate.info с информацией о дате и времени последнего обновления.
* Информацию о новых версиях ConEmu получает по [этому адресу](http://conemu-maximus5.googlecode.com/svn/trunk/ConEmu/version.ini). В случае необходимости (например, централизованное обновление компьютеров в сети?) адрес можно изменить через reg/xml (поле "Update.VerLocation").



## x64 issues  {#q-5-x64}




#### Q. Зачем нужны файлы ConEmuC.exe, ConEmuCD.dll и ConEmuHk.dll в 64битных ОС?   {#q-5-1}


A. Эти файлы необходимы для запуска 32битных приложений, а также для работы 32битной версии ConEmu.exe. Наверняка в какой-то момент вам окажется необходимо запустить 32битную консольную программу. Без этих файлов это не получится. В принципе, можно пользоваться 64битной версией ConEmu64.exe, которая доступна в дистрибутиве «`ConEmuSetup.*.exe`», она запускает ConEmuC64.exe в качестве корневого консольного процесса.




#### Q. Зачем нужны файлы ConEmuC64.exe, ConEmuCD64.dll и ConEmuHk64.dll в 32битной версии ConEmu?   {#q-5-2}


A. Эти файлы необходимы для запуска 64битных приложений в 64битных ОС.




#### Q. При запуске команд start, echo (и прочих команд cmd.exe) на 64битной ОС возникает ошибка вида "File not found. Cannot execute. start".   {#q-5-3}


A. Скорее всего вы удалили необходимый файл ConEmuC64.exe и сопутствующие ConEmuHk64.dll, ConEmuCD64.dll.




#### Q. При попытке запуска (из Far Manager) возникает системная ошибка вида: «Ошибка при запуске приложения (0xc0000142). Для выхода из приложения нажмите кнопку "OK".»   {#q-5-4}


A. Причина пока не найдена, какая-то проблема в Windows. Причем, ошибка возникает не только в ConEmu, но и в 'чистой' консоли. Для восстановления нормальной работы нужно перезапустить консоль (например через Win-~).




#### Q. Что происходит с переменными окружения в 64битных OS?   {#q-5-5}


A. ConEmu не управляет переменными окружения.




## Настройка  {#q-6-settings}




#### Q. Можно ли запустить ConEmu так, чтобы в нем сразу было открыто несколько вкладок: Far, CMD, PowerShell?   {#q-6-1}


A. Можно. Для этого используйте командный файл запуска. Например **startup.txt**:

~~~
>E:\Source\FARUnicode\trunk\unicode_far\Debug.32.vc\far.exe
*/BufferHeight 400 cmd
/BufferHeight 1000 powershell
~~~

и запускайте ConEmu так:

~~~
conemu.exe /cmd @startfile.txt
~~~

В файле каждая строка соответсвует запускаемой команде. Допустимо указание в строке параметра /BufferHeight для установки высоты консольного буфера. Если в начале строки стоит "`>`" - эта консоль будет активной после завершения запуска. Если в начале строки стоит "`*`" - эта консоль будет запущена под администратором.




#### Q. Двоятся окна Far Manager.   {#q-6-2}


A. Это просто консольное окно не спряталось. Проверьте флажок 'Visible' на вкладке 'Features' окна 'Settings' или значение в реестре:

~~~
[HKEY_CURRENT_USER\Software\ConEmu\.Vanilla]
"ConVisible"=hex:00
~~~



#### Q. Как настроить растровый шрифт?   {#q-6-3}

A. Это шрифт Terminal. Например консольный '8 x 12' это 'Terminal 12 x 8' в ConEmu, '12 x 16' -> 'Terminal 16 x 12', и т.п.

> Внимание: В поле 'Charset' необходимо выбрать 'OEM'.
> Лично мне нравится 'Fixedsys 16 x 8', которого в обычной консоли нет.


A. В списке шрифтов можно сразу выбрать, например, `[Raster Fonts 8x12]`.




#### Q. Почему горизонтальные рамки отображаются пунктиром/прерывисто?   {#q-6-4}


A. В некоторых шрифтах ширина соответствующих символов псевдографики оказывается меньше заявленной средней ширины символов шрифта, а именно на него ориентируется ConEmu при автоматическом выборе размеров шрифта рамок. Чтобы избавиться от пунктира, включите флажок «Fix Far borders» и увеличьте ширину шрифта для рамок. Поля имени и ширины шрифта дл рамок расположены под флажком «Fix Far borders» на вкладке 'Main' окна 'Settings'.




#### Q. Как запустить несколько консолей в сетке 2x2   {#q-6-5}


A. Вопрос с [superuser.com](http://superuser.com/q/473807/139371). ConEmu (рекомендуется build 120909 или выше) может отображать несколько консолей одновременно ([SplitScreen](SplitScreen.html)). Вы можете создать задачу (Task) запускающую несколько консолей, например, в сетке 2x2.

~~~
>cmd -cur_console:n
cmd -cur_console:s1TVn
cmd -cur_console:s1THn
cmd -cur_console:s2THn
~~~



#### Q. Как настроить запуск cmd.exe под Администратором из контекстного меню Проводника Windows   {#q-6-6}


A. Читайте ответ на [superuser.com](http://superuser.com/q/470408/139371).




#### Q. Как поименовать запускаемые табы при запуске из задачи {Task}   {#q-6-7}


A. Читайте ответ на [superuser.com](http://superuser.com/q/459154/139371).




#### Q. Как настроить Git Bash Here в ConEmu   {#q-6-8}


A. Читайте ответ на [superuser.com](http://superuser.com/q/454380/139371).




#### Q. Как экспортировать настройки ConEmu   {#q-6-9}


A. Читайте ответ на [superuser.com](http://superuser.com/q/450144/139371).




#### Q. Как прицепить открытое консольное окно в новый экземпляр ConEmu   {#q-6-10}


A. Читайте ответ на [superuser.com](http://superuser.com/q/445394/139371).




#### Q. Как удалить пункты из списка «Create new console»   {#q-6-11}


A. Читайте ответ на [superuser.com](http://superuser.com/a/436273/139371).




## Far Manager  {#q-7-far}




#### Q. Почему не работают табы (вкладки)?   {#q-7-1}


A. Плагин ConEmu.dll (ConEmu.x64.dll) установлен?


A. При использовании инсталлятора плагин ConEmu.dll мог быть установлен в неправильную папку, нужно ставить в подпапку Plugins для Far.exe. Инсталлятор мог не найти папку Far.exe, если Far был установлен не через msi. Проще всего сделать Uninstall для ConEmu и установить его заново, но убедиться, что для элемента 'Far Manager plugins' указана корректная папка.


A. Флажок 'Enable Tabs' в настройке включен? Если флажок в 'третьем состоянии' табы появляются только после открытия редактора/вьювера.




#### Q. Почему не работает (плагин) Drag-n-Drop?   {#q-7-2}


A. «Shell style Drag and Drop» встроен в ConEmu и настраивается на вкладке 'Far Manager' окна 'Settings'. ConEmu умеет вытаскивать файлы «наружу» в другие приложения (проводник, GIMP, и т.п.) и принимать файлы внутрь (на панели и командную строку) из других приложений. Для корректной работы «Shell style Drag and Drop» в Far должен быть установлен плагин ConEmu.dll (ConEmu.x64.dll). ConEmu может драгать файлы как левой (флажок LDrag) так и правой (RDrag) кнопками мышки. Опционально можно назначить модификатор, например драгать файлы левой кнопкой только при удерживаемом LCtrl.


A. Скриншоты и некоторые пояснения можно посмотреть/почитать здесь:
[Issue 527](http://github.com/Maximus5/conemu-old-issues/issues/527).


A. Плагин (сторонний) Drag-n-Drop не поддерживался, не поддерживается и поддерживаться не будет, т.к. эта функциональность встроена в ConEmu.




#### Q. Как закрыть таб (редактор/вьювер/фар) мышкой?   {#q-7-3}


A. При удерживании Ctrl 'правый щелчок' мышки активирует таб и сразу посылает в Far Manager макрос закрытия. Вы можете переопредлить макрос на вкладке 'Far Manager' окна 'Settings', поле 'Close tab'.


A. Без удерживания Ctrl 'правый щелчок' мышки активирует таб и отображает контекстное меню, в котором можно выбрать пункт 'Close'.




#### Q. В Far не передаются нажатия кнопок мышки, колесо.   {#q-7-4}


A. Проверьте настройку Far -> Interface settings -> `[x]` Mouse.


A. Если Far работает в режиме «far /w» (System\WindowMode=1) то необходимо наличие плагина ConEmu.dll (ConEmu.x64.dll), иначе ConEmu будет считать что сейчас работает обычное консольное приложение типа cmd.exe в которое событие мышки посылать не нужно.




#### Q. Почему не работает плагин FarHints?   {#q-7-5}


A. Его необходимо обновить (версия 1.0.15 и выше) и он требует наличия плагина ConEmu.dll (ConEmu.x64.dll).




#### Q. В какой-то момент перестают работать табы, Drag-n-Drop,...   {#q-7-6}


A. Посмотрите на вкладку 'Info' окна 'Settings'. Скорее всего не включен статус 'Far' или 'Panels'. Учтите, что для D&D необходим плагин ConEmu.dll (ConEmu.x64.dll).




#### Q. По щелчку правой кнопкой мышки не появляется контекстное меню для файла/папки.   {#q-7-7}


A. Не включен флажок 'RightClick 4 context menu'? Если флажок в 3-м состоянии - меню появляется после 'долгого' клика, дождитесь пока замкнется кружок вокруг курсора мышки.


A. По какой-то причине ConEmu не обнаружил 'панели' в Far. Может быть не установлен плагин ConEmu.dll (ConEmu.x64.dll)? Если все-таки установлен - присылайте скриншоты ConEmu, вкладки 'Info' окна 'Settings' и файл 'Dump screen...' (системное меню ConEmu -> Debug -> Dump screen...).




#### Q. По щелчку правой кнопкой мышки появляется графическое меню, а хочу текстовое.   {#q-7-8}


A. Соответствующий макрос можно указать на вкладке 'Far Manager' окна 'Settings'. Например: `F11 e Enter 2`. Предполагается, что для EMenu назначен hotkey 'e'.




## Windows Vista  {#q-8-vista}




#### Q. В Windows Vista не срабатывает комбинация Ctrl-Win-Alt-Space для показа RealConsole.   {#q-8-1}


A. Почему-то первое наатие пробела вистой иногда 'проглатывается'. Не отпуская Ctrl-Win-Alt нажмите пробел еще раз.




#### Q. В Windows Vista зависают другие консольные процессы.   {#q-8-2}


A. "Виноват" процесс ConIme.exe. Вроде бы он служит для ввода иероглифов (китай и т.п.). Зачем он нужен, если ввод теперь идет в графическом окне? Нужно запретить его автозапуск или вообще переименовать этот файл, например в 'ConIme.ex1' (видимо это возможно только в безопасном режиме). Запретить автозапуск: Внесите в реестр и перезагрузитесь

~~~
[HKEY_CURRENT_USER\Console]
"LoadConIme"=dword:00000000
~~~



## Аварийные завершения  {#q-9-crash}




#### Q. При завершении консольной программы возникает ошибка вида: Access violation at address 6F78DE5B in module 'ConEmuHk.dll'. Read of address 0071004E   {#q-9-1}


A. Возможная причина - эта консольная программа порушила свою таблицу импортов. Решение - обратиться к ее разработчику. Для более точного вердикта "кто виноват" можно прислать мне [минидамп](MemoryDump.html).




#### Q. ConEmu или консольное приложение зависает при выходе?   {#q-9-2}


A. Ни одного Issue на эту тему еще не было создано. Тем не менее, если случилось зависание при выходе, сделайте [дампы памяти](MemoryDump.html) процессов ConEmu`*`.exe, ConEmuC`*`.exe и и всех процессов этой консоли (far.exe, cmd.exe, ...). Как это сделать смотрите ниже. Заархивировать и прислать файлы разработчику. Для создания правильного дампа 32битного приложения в 64битной ОС нужно использовать ConEmu.




#### Q. Как создать дамп памяти приложения?   {#q-9-3}

A. **Windows XP и выше.**

Нажмите `Win+R` и введите команду, она создаст полный дамп памяти процесса (может быть довольно большим).

~~~
C:\Program Files\ConEmu\ConEmu\ConEmuC.exe /DEBUGPID=ИД_Процесса /FULL
~~~
Или другую команду, для создания малого дампа памяти. Малый дамп, к сожалению, может не содержать необходимой информации.
~~~
C:\Program Files\ConEmu\ConEmu\ConEmuC.exe /DEBUGPID=ИД_Процесса /MINI
~~~

Вам будет предложено выбрать имя файла дампа памяти процесса. Как узнать `ИД_Процесса` читайте ниже.

Внимание!** При создании дампов Far Manager убедитесь, что вы запускаете "far.exe" с ключом "/x".

A. **Windows 7 и выше.**

*Внимание! Этот метод допустим только для процессов той же битности, что и OS.
То есть создать корректный дамп для 32битного процесса в 64битной OS не получится.
Открыть Диспетчер задач Windows, перейти на вкладку 'Процессы' и в контекстном меню
выбрать пункт 'Создать файл дампа памяти'.*

A. **Process Explorer.**

Дампы памяти умеет создавать утилита «Process Explorer»,
но *с ее помощью создать корректный дамп для 32битного процесса в 64битной OS также не получится*.



#### Q. Как узнать ИД процесса (PID)   {#q-9-4}


A. Идентификатор процесса (PID) можно узнать по имени процесса (ConEmu.exe, cmd.exe, etc.)

* в Диспетчере задач Windows на вкладке Процессы есть колонка *ИД процесса*;
* в строке статуса ConEmu;
* в диалоге [Settings](Settings.html#Info) на вкладке «Info».

**Примечание!** В некоторых случаях колонка *ИД Процесса* может не отображаться в Диспетчере задач Windows.

* Windows 7 и ниже: Диспетчер задач -> Вкладка «Процессы» -> Меню -> Вид -> Выбрать столбцы -> «PID».
* Windows 8: Диспетчер задач -> Включить «More details» -> Вкладка «Процессы» -> Правый клик мышкой на заголовке колонок -> «PID».



#### Q. Как запустить Диспетчер задач Windows   {#q-9-5}


A. Нажмите **Ctrl+Shift+Esc** или щелкните правой кнопкой мышки по панели задач и выберите пункт меню «Диспетчер задач».




#### Q. Что означает: ConEmuC: CreateFile(CONOUT$) failed, ErrCode=0x00000005   {#q-9-6}


A. Запускаемая программа создала и установила в консоли собственный буфер,    созданный как `CreateConsoleScreenBuffer(..., 0/*No sharing*/, ...)`. Просите автора программы создавать буфер корректно, а не только для себя:

~~~
(GENERIC_READ|GENERIC_WRITE, FILE_SHARE_READ|FILE_SHARE_WRITE,...)
~~~



## Unsorted  {#q-10-unsorted}




#### Q. Как сворачивать ConEmu в трей (в иконку рядом с часами)?   {#q-10-1}


A. Щелкнуть правой кнопкой по крестику в заголовке. Можно также включить флажок 'Auto minimize to TSA' в настройке. Тогда сворачивание в трей будет происходить автоматически при минимизации.




#### Q. Зачем ConEmu меняет шрифт у реальной консоли?   {#q-10-2}


A. В реальной консоли должен быть выбран TrueType шрифт, иначе в ConEmu вместо юникодных символов (иероглифы, троеточие, копирайты, и пр.) будут отображаться знаки вопроса ('?'). Так устроена консоль Windows.


A. Размер шрифта в реальной консоли должен быть меньше, чем ConEmu, иначе будет невозможно увеличить размер ConEmu (в символах) более того размера, который разрешен в Windows для текущего консольного шрифта.




#### Q. Почему-то отображается только часть консоли; консоль отображается сдвинутой; не отображается вообще.   {#q-10-3}


A. В настройке (Settings-ConEmu.reg) указан слишком большой консольный шрифт.


A. Возможно, выбрана слишком большая ширина окна (в символах).


A. Возможно, по какой-то причине ConEmu не смог сменить шрифт у реальной консоли. Выберите пункт системного меню окна ConEmu 'Properties' и на закладке 'Шрифт' выберите TrueType шрифт и наименьший размер.




#### Q. Почему исчезает окно быстрого поиска в панелях при переключении языка?   {#q-10-4}


A. Так получилось. ФАР убирает окно поиска при потере и получении фокуса. Включите флажок 'Skip focus events' на вкладке 'Features' окна 'Settings'.




#### Q. Почему нет кнопок мультиконсоли на панели инструментов?   {#q-10-5}


A. Включите флажок 'MultiCon' в настройке, или ключ /Multi в командной строке.




#### Q. Зависает (в заголовке ConEmu отображается '...Waiting for result (10 sec)') через некоторое время в FAR появляется меню плагинов (или вызывается какой-то другой плагин).   {#q-10-6}


A. По какой-то причине ConEmu не смог определить, что Far не отвечает на запросы пользователя (выполняется команда, ожидание, и т.п.).




#### Q. Почему не отображается 'Background image'?   {#q-10-7}


A. По умолчанию, выбранным изображением замещаются только цвета фона #0 и #1 (обычно это черный и синий). В вашей настройке цвета могут быть другими, для явного указания замещаемых цветов можно использовать параметр "bgImageColors".


A. Если флажок 'Background image (bmp)' в третьем состоянии - картинка отображается только в панелях.


A. Если флажок 'Background image (bmp)' включен и файл картинки выбран - проверьте значение 'Darkening'. Возможно там указан 0.




#### Q. Зачем нужно подтверждение 'Press Enter to close console...' отображаемое перед закрытием консоли после завершения всех программ в ней?   {#q-10-8}


A. Если консоль будет сразу закрываться - вы не увидите ни результата выполнения команды, ни сообщений о возможных ошибках в аргументах.




#### Q. Как отключить 'Press Enter to close console...'?   {#q-10-9}


A. Подтверждение закрытия отключается автоматически после того как:

* корневая консольная программа проработает более 10 секунд, или
* запускается FAR, как корневой процесс, и в нем загружен плагин ConEmu.

A. При запуске команды можно добавить параметр `-new_console:n`.




#### Q. Запускается FAR, плагин установлен, но все равно появляется 'Press Enter to close console...'?   {#q-10-10}


A. Возможно, в качестве корневого процесса запустился на FAR, а cmd.exe. Проверьте список процессов на вкладке 'Info' окна 'Settings'. Причина - некорректная командная строка (аргумент /cmd в ConEmu), возможна ошибка в некорректных кавычках.




#### Q. Почему Shift-Enter в панелях запускает новое окно с реальной консолью, а не в новой вкладке?   {#q-10-11}


A. Отсутсвует макрос на Shift-Enter или макросы запрещены.


A. Shift-Enter нажат во время 'быстрого поиска' (в этом случае требуется расширенный макрос для макрообласти 'Dialog').




#### Q. Почему в консоли отображается прямоугольник (рамка) вместо курсора?   {#q-10-12}


A. Опция 'Block inactive cursor'. Альтернативная индикация, что фокус не в консоли.




#### Q. В табах отображаются квадратики (вместо иероглифов).   {#q-10-13}


A. По умолчанию, текст закладок отображается шрифтом "Tahoma". Выберите другой шрифт, содержащий требуемые вам символы (например "Arial Unicode MS") на вкладке 'Tabs' окна 'Settings'.




#### Q. Для консоли ConEmu не всплывает перевод GoldenDict   {#q-10-14}


A. Обновите GoldenDict до версии [1.0.1-271](http://goldendict.org/forum/viewtopic.php?p=7835#p7835) или более поздней.
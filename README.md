# Linux-OS8.0-X64-18.10
Linux , Ubuntu , 18.10 , iso , X64 , Gnome , Cinnamon , XFCE , Unity , Budgie , iso

Linux OS8.0 X64 2020 iso download : https://yadi.sk/d/zP9YWq_Wuv1qnw

---------------------------------------------------------------------------------------------------------------------------

+ Если кому надо вот в придачу Android 

Android 8: https://yadi.sk/d/u7McqXikcZC6Lw

Android 7.1: https://yadi.sk/d/rlrR6hdaBz0mWA android 7 https://www.youtube.com/watch?v=ua_QQNJtKE8

Для тех кто будет программировать на системе что бы не бояться что она поломается там установлен timeshift

После того что какие проблемы то читать в Читать.txt

Понадобиться флешка с 4 гигабайтами для того что бы образ влез , 
можно взять флешку и не стирая её закинуть туда образ программой Ultra ISO , WinSetupFromUSB_1-0 
или программой (unetbootin не помню стирает она данные или нет перед прожигом) , 
точный пример без потери данных на флешке WinSetupFromUSB_1-0 выставив галки 
как на картинке https://imgur.com/a/7NugSRA , потому что не у всех есть флешка лишняя и так этот способ даст избежать лишних затрат на флешки , 
в play market тоже есть утилиты типа DriveDroid и другие с помощью которых можно 
даже с телефона установить по кабелю с ПК и установить образ со смартфона.
Для linux я использую https://unetbootin.github.io/linux_download.html просто делаете бинарник в свойствах
исполняемым и либо запускаете от админа или в терминал в той же папке руню рутирую и закидываю в его окно бинарь 
образ указываю предварительно смонтировав флешечку которая предварительно отформатирована не меньше чем fat32

Установка 

Flesh card / hdd / usb hdd / sdd / vhd / vhdx minimum size memory 16 gb

Как проверить любой дистрибутив , надо открыть настройки vlc плеера если вылетит значит не годится

Systemback также поможет восстановить систему и отремонтировать grub её и ваши фаилы не пропадут 
если они лежат именно в папке home , только пропадут программы которые установили после , это очень 
удобно на днях я попытался скомпилировать и разработать свой xorg-server в итоге ни клавиатура не 
мышь не работали и с помощью systemback я восстановил систему без всяких переустановок просто подмонтировал 
свой sd раздел в /mnt и включил восстановление системных файлов.

 svn support можно сделать jhalfs blfs с java машинамм уже готовыми для работы с java и snapd в более верхних новых дистрибутивах придется устанавливать официальное ядро которое будет подерживать snap и dkms что бы крутить тот же anbox фаил upstart-OS8.0_Demo_Griggorii.tar.bz2 только для этой системы так что возможно скоро upstart заработает. Ядро в этой версии рабочее , но выше можете понизить ядро и посмотреть будет оно лучше или нет.
java version "1.8.0_201". 
Внимание системные репы куда то исчезли уже с где то с 19 февраля возможно они поняли что это лучшая ось за счёт того что не ломается от сраных suda make install вообщем форкаем под моим ником и тянем мою ось не даром я тогда говорил что я её смешивал и регулятор регулировки яркости рабочии даже в budgie окружении. Так же подготовленна новая графика mesa тут готовый пакет или сорцы https://github.com/Griggorii/mesa-13.0.4_V2_source_by_Griggorii_tutorial_patent_compilation т.е работа из за отсутствия реп заморозилась видимо пересматривают и понимают что это операционная система лучшая по этому все репы отняли что бы не смогли билдить на этой смешанной системе впрочем и тут они пропали https://pkgs.org/ и дабы подтвердить что не у меня одного я загуглил https://superuser.com/questions/1527250/apt-update-error-with-ubuntu-18-10-cosmic-version фактически они поняли что все более новые системы это шлак где очень важные папки собраны ссылками чем и допущена самая их фатальная ошибка и тут не надо обижаться я знаю каждый хвалит своё болото , но столкнуться с этим когда ты занимаешься костимизированным билдингом где программы должны делать какие то новые нано функции и развалиться на простой команде sudo make install через некий sed это вообще нечто что выходит за грани разумного я люблю свою работу и не могу рисковать своими билдами которые должны не ломать систему , а нормально собирать все в пакет , а ковырятся где то еще особо затратно в некоторых местах да есть deb пакеты , но их качать будешь искать версию по зависимости трудно затратно и зарплаты не видно даже донеитов нету , пришлось временно curl4 на curl3 переключить. Короче опять не тем зарплату платят надеюсь это не макеры там замахнулись купить эту ось что бы в свою перемаркировать. Видимо графику можно ускорить с моим пакетом /etc/ld.so.conf.d надо будет перебить конфиги на расположение драиверов mesa потому что щас egl с которым я собрал mesa уже не по пути /usr/lib/x86_64-linux-gnu/mesa , а /usr/lib/x86_64-linux-gnu/ фактически после установки моего пакета с mesa можно сделать rm -rf /usr/lib/x86_64-linux-gnu/mesa так как те направленны на старую mesa от 16.04 который я разрабатывал очень давно и был на основе linux lite который позднее превратился в пеперминт ксениал. Возможно вы понимаете что я создал эту операционную систему для компиляции всего что только возможно что бы перенести всё на новые системы то что нельзя перенести на официальных версиях как и с тем же blfs и поддержкой svn , как вы видите если вы девелопер и вам помогла моя система как остров перехода и легко скомпилировали и отдали работу на другие системы получили свой миллион долларов за какой нибудь серн то мой кошелек есть в описании , а там поддержите меня значит поддержите переносимость кода.
Как пример https://github.com/Griggorii/mesa-19.0.1_source_griggorii_mit_patent_llvm-7 я делал на OS8.0 в следствии пришлось разгадывать клубок на затыках так как я передупреждал что я смешивал с 16.04 то позднее оттуда методом cp перекинул llvm и clang фаилы даже проблема с aubinator от intel удалось понять почему затык и исправить эту ошибку перебросив пару фаилов из 16.04 системы что я ранее создал. В следствие чего люди которые заняли места и они им не жмут отрезали репы узнав что этот дистрибутив может то что другие просто не смогут сконфигурировать и скомпилировать код для переноса на различные системы и не только , а не только с линукса на линукс.  Так что если они где то начнут продавать не свою работу в образе iso то сразу показывайте им кто создатель что бы не было отсебятской торвальдьсятины и прочих аграриев.

Java(TM) SE Runtime Environment (build 1.8.0_201-b09)

Java HotSpot(TM) 64-Bit Server VM (build 25.201-b09, mixed mode) 

Линковка $$java mkdir ~/.mozilla/plugins && ln -s /usr/lib/jvm/java-8-oracle/jre/lib/amd64/libnpjp2.so ~/.mozilla/plugins/ 

При установке пароль для себя делайте только на латинице с цифрами или и так и так по отдельности после установки в первое окружение которое вы попадете если вы включали автовход будет unity просто жмем выйти и потом в центральном окне находим себя , а сверху в в самом краине правом углу выбираем cinnamon / budgie / ubuntu / или xfce в самом низу будет по русски другое название типа сессия и далее после забиваем пароль и опять в краинем правом углу смотрим что бы галка сессии не перепрыгнула , а там есть такое она иногда прыгает так что точно уже после ввода пароля видно. В окне выбора сессии в верхнем правом углу не трогайте выбор языка это для окружения и на данны момент там ru т.е простыми словами это не является выбором раскладки.
В документах после установки будет лежать патч для интел видео карт linux_xorg_glamor_perfomance_uxa_tearing_fix_intel что бы использовать ускорение интел установите xserver-xorg-video-intel и даст прирост скорости в 3 - 4 раза после его установки больше и выполните скрипты из архива linux_xorg_glamor_perfomance_uxa_tearing_fix_intel если у вас интел.
Alt+F2 иногда если есть с клавишей FN вызов быстрого поиска в моей системе сразу много окружении что бы можно было выбрать 
так как я все их настроил и уже даже dconf root-a xfce тоже настроен с помощью моих конфигов все они находятся в etc/skel и перебросить можно хоть куда в случае потери чего либо например с live диска с очищением той же папки .cache .
В cinnamon включены звуки вы можете их выключить для этого откройте регулятор громкости pulse audio переидите на вкладку 
проигрываание -  > системные звуки и одерните ползунок в обе стороны и до уменьшения громкости и теперь интерактивные звуки что я настроил в  dconf проигрываться не будут и мешать тоже. XFCE4 тиринг так и не убрали и если вы хотите проверить есть ли 
у вас тиринг то вам сюда https://youtu.be/J7HbQ246W7s отпишитесь на каких дистрибутивах с этим конфигом нету тиринга , то какие то гении убрали пункт "вертикальная синхронизация" при том что в самом новом релизе и версии xfce4 и я подумаю над тем что бы собрать его с моими настройками и темами если конечно будет некий упаковщик по примеру который в  deb.

Make для понижения если не будет компилироваться какой нибудь ffmpeg , ядро или всякие сложные вещи

Для тех кто работает на java я некогда на версии 18.10 вручную из 16.04 делал переброс джавы ну и роясь в var нашел что видимо у меня там целые компиляторы собрались открыв архивом я обнаружил что все целое и решил закинуть для дальнейших разработок сюда предварительно запаковав в tar.gz.

oracle-jdk8-installer https://drive.google.com/open?id=18qpAHed7sMZ3shXx1lZvgj9rvTkt1poQ

google-android-platform-24-installer https://drive.google.com/open?id=1KG3tNbxdTZB3bt8Zzing7Owhaay9wyOM

Очень много происходит в var папке например недавно при обновлении grub я обнаружил что раздел от оси гугл хрома , а нравится 
он мне не из за ndk , а из за того что может в своём кожухе уже крутить двигатель андроида оставаясь при этом линуксом правда 
без апт и дпкг так вот при обновлении я в убунту груб я обнаружил в папке var на время появился весь контейнер из opt хрома оси при том что чего либо другого не было т.е по сути этот раздел можно использовать под андроид на убунте и это будет примерно как opt в хром оси и уже используют вот тот же anbox и все это начиналось с 16.04 потому что именно там шнап уже начинал ставить то что не возможно поставить из за того что библиотека glib устарела. Как говориться пока у кого то гента 
мержится в opt у меня это делает var при том что он там компилирует даже джаву и котлин. Сама система в которую я ещё раз повторяю вытащил из 16.04 java машину и всю по частям перенес это OS 8.0 18.10 скачать её можно ниже внимание не создавайте раздел efi в нем нету этого загрузчика так как он не установлен при установке проще говоря только все в один раздел <</>> https://github.com/Griggorii/Cinnamon-Budgie-OS-4.0-beta-based-18.04/blob/master/README.md страницу надо промотать вниз.
Так же скачать настройки от более новых OS моего настройства и применить скрипты что бы получить отличный новый дизаин https://github.com/Griggorii/linux_setting_dconf_linux_OS19_By_Griggorii



Система бесплатная и как донат могу принять плюс или минус за неё на ютубе можете её обновить до 19.10 и она будет более 
стабильная чем ту что вы скачаете и если вам как и мне не нужен zfs , так же приветствуется если вы выпустите ролик и покажете как вы меняете различные ДЕ окружения как они выглядят настроенными руками которые уже имеют более опыта так как я не могу показать по скольку нужно виртуалку заводить а , ноутбук слабый и из за того что все переехало на GTK3 , а точнее просто поменяло фактически название то потребляемость выросла , но как говорится оставляем из за того что бы не скачивать флатпаки и шнапы что бы не иметь кучу зоопарковых разветвлении системы тот же pulseeffects допустим в 16.04 это либо флатпак либо шнап т.е нету единой эко системы , по этому особо выхода нет , а то ещё вдруг там какие уязвимости позднее найдут.
Если кто может объяснить другая страна и язык то им надо будет удалить фаил /etc/default/locale если допустим им язык надо на 
какой нибудь своей страны поменять , я просто не знаю меняется ли он при установки потому что я пользуюсь ru языком.
Если вы считаете что эта система плохая и нужно ставить с ноля то делайте , а потом заидите после установки в /lib/systemd/system и проверьте есть ли там битые ссылки , но я не директор и не могу исправить то что портят даже за деньги 
по этому просто предупредил.

---------------------------------------------------------------------------------------------------------------------------


Про интернет соединение без роутера https://www.youtube.com/watch?v=mAUXs3WLuug у вас должно быть там всё на родном языке.
step 3: save правильнее , после step 3 yes ничего не делаем и выходим из терминала.
Потом у меня ниже на панели есть network-manager апплет зайдите щёлкнув на него либо лкм или пкм (потому что я не знаю как ваша мышь работает программно или настроена) изменить соединения и удаляете созданные проводное и Автоматический Ethernet и dsl соединение.

Затем жмёте + и создать из списка выбираете DSL/PPPoE

Соединение DSL 1 , 
предковый интерфейс enp2 , 

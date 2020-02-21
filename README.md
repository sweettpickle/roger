# roger
Rojer

Дать судо права:
http://fkn.ktu10.com/?q=node/9509
Права пользователей в Linux. Команды sudo и su
https://www.xelent.ru/blog/prava-polzovateley-v-linux-komandy-sudo-i-su/


Настройка статического IP адреса в Unix/Linux:
https://linux-notes.org/nastrojka-staticheskogo-ip-adresa-v-debian-ubuntu-linux-mint/


Как поменять (изменить) порт у SSH сервера:
https://firstwiki.ru/index.php/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D0%BC%D0%B5%D0%BD%D1%8F%D1%82%D1%8C_(%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B8%D1%82%D1%8C)_%D0%BF%D0%BE%D1%80%D1%82_%D1%83_SSH_%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B0
что такое порт
https://2ip.ru/article/ports/


Работа с сетями в VirtualBox
http://lifeslider.blogspot.com/2012/07/virtualbox.html?m=1
Настройка сети в VirtualBox
http://rus-linux.net/MyLDP/vm/VirtualBox-networking.html
VirtualBox доступ в интернет из гостевой системы и доступ к гостевой системе (!)
https://web-programming.com.ua/virtualbox-dostup-v-internet-iz-gostevoj-sistemy-i-dostup-k-gostevoj-sisteme/
НАСТРОЙКА СЕТИ VIRTUALBOX
https://losst.ru/nastrojka-seti-virtualbox
ПРОБРОС ПОРТОВ VIRTUALBOX
https://losst.ru/probros-portov-virtualbox


Как Настроить SSH-ключ
https://www.hostinger.ru/rukovodstva/kak-nastroit-ssh-klyuch
Создание и настройка ключей OpenSSH
https://hackware.ru/?p=9939#41


Firewall 
https://losst.ru/nastrojka-ufw-ubuntu#2

https://speed-tester.info/info_17_chto_takoe_firewall_i_dlja_chego_on_nuzhen_faervol_dlja_setevoj_zaschity_kompjutera.html
Настройка брандмауэра в Ubuntu 18.04
https://www.xelent.ru/blog/Nastrojka-brandmauehra-v-Ubuntu/


DoS-атаки: просто о сложном
http://www.iksmedia.ru/articles/5142418-Zashhita-ot-DoSataki-prosto-o-slozh.html

воспроизвести атаки:
slowloris
https://github.com/gkbrk/slowloris
Wreckuests — скрипт для DDoS-атак
https://yougame.biz/threads/18600/

Защита
Fail2ban и аналоги
https://jpnsoft.ru/fail2ban/
Как защитить себя от DoS/DDoS-атак
https://05.xn--b1aew.xn--p1ai/document/1108566
Защита от ddos атак (!)
https://linux-notes.org/zashhita-ot-ddos-atak/


Настройка Fail2ban для защиты SSH
https://www.dmosk.ru/instruktions.php?object=fail2ban
тож
https://putty.org.ru/articles/fail2ban-ssh.html
Настройка и использование Fail2ban на Linux
https://linux-notes.org/zashhita-ot-ddos-atak/
Установка и настройка Fail2ban. Защита ssh сервера
https://itproffi.ru/ustanovka-i-nastrojka-fail2ban-zashhita-ssh-servera/


Открытые порты
https://losst.ru/kak-posmotret-otkrytye-porty-v-linux
Nap


Вы должны установить защиту от сканирования на открытых портах вашей виртуальной машины.
https://blog.tiukov.com/all/linux-zaschischaemsya-s-pomoschyu-portsentry/

http://samag.ru/archive/article/154

Обновление пакетов
https://tyapk.ru/blog/post/how-to-upgrade-ubuntu-in-terminal





Настройка ssl 
Nginx
https://www.8host.com/blog/sozdanie-samopodpisannogo-ssl-sertifikata-dlya-nginx-v-ubuntu-16-04/

Apache
https://www.8host.com/blog/sozdanie-samopodpisannogo-ssl-sertifikata-dlya-apache-v-debian-9/


http://sysadm.pp.ua/linux/iptables-antiscan.html

http://www.linuxrsp.ru/artic/portsentry3.html


sudo service --status-all
systemctl list-unit-files --type service --state
enabled



85 AppArmor — программный инструмент упреждающей защиты, основанный на политиках безопасности (известных также как профили), котор    ые определяют, к каким системным ресурсам и с какими привилегиями может получить доступ то или иное приложение. В AppArmor вклю    чён набор стандартных профилей, а также инструменты статического анализа и инструменты, основанные на обучении, позволяющие уск    орить и упростить построение новых профилей
 86
 87 getty@.service (сокращение от get teletype) — программа для UNIX-подобных операционных систем, управляющая доступом к физически    м и виртуальным терминалам (tty). Программа выполняет запрос имени пользователя и запускает программу 'login' для авторизации п    ользователя.
 88
 89 autovt@.service - Является симлинком на getty@.service. В том случае, если нам нужен какой-то конкретный VT. За это отвечает lo    gind, который при переключении на ttyN запускает сервис autovt@ttyN.service
 90
 91 cron — классический демон (компьютерная программа в системах класса UNIX), использующийся для периодического выполнения заданий     в определённое время. Регулярные действия описываются инструкциями, помещенными в файлы crontab и в специальные каталоги.
 92
 93 D-Bus — система межпроцессного взаимодействия, которая позволяет приложениям в операционной системе сообщаться друг с другом.
 94
 95 Rsyslog - это программная утилита с открытым исходным кодом, используемая в UNIX и Unix-подобных компьютерных системах для пере    сылки сообщений журнала в IP- сети . Он реализует базовый протокол системного журнала , расширяет его фильтрацией на основе сод    ержимого, широкими возможностями фильтрации, операциями с очередями для обработки автономных выходов [2] , поддержкой различных     выходов модуля [3] , гибкими параметрами конфигурации и добавляет такие функции, как использование TCP для транспорта.
 96
 97 Syslog (англ. system log — системный журнал) — стандарт отправки и регистрации сообщений о происходящих в системе событиях (то     есть создания событийных журналов), использующийся в компьютерных сетях, работающих по протоколу IP. Термином «syslog» называют     как ныне стандартизированный сетевой протокол syslog, так и программное обеспечение (приложение, библиотеку), которое занимает    ся отправкой и получением системных сообщений.
 98
 99 systemd-timesyncd - это демон, который был добавлен для синхронизации системных часов по сети. 

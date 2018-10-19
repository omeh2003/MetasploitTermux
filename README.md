# MetasploitTermux
Metasploit на любой андроид девайс. С адекватным кол-вом оперативки что бы билдить код. 

Root не нужен

Нужен терминальный клиент для Android Termux из PlayMarket https://play.google.com/store/apps/details?id=com.termux&hl=ru

И набор команд из файла в проекте. 

Самый простой путь. Постаить Termux. Запустить его и вести:
1. apt update && apt upgrade
2. apt install curl
3. curl -LO https://github.com/omeh2003/MetasploitTermux/blob/master/metasploit.sh
4. chmod a+x metasploit.sh
5. ./metasploit.sh

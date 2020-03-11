# tramden
***************************************
Клонирование Websites  и удаленое логирование 
С возможностью подключения к Ngrok
***************************************
УСТАНОВКА ТОЛЬКО С ПРАВАМИ СУПEР ПОЛЬЗОВАТЕЛЯ

$ sudo apt update && apt upgrate

$ sudo apt install git

$ sudo apt install python -y  && $ sudo apt install python2 -y

$ git clone https://github.com/bednakovdenis/tramden.git

$ cd

$ ls

$ cd tramden

$ chmod +x tramden.py 

$ sudo python2 tramden.py 

Далее пишем show и видем такую таблицу
	--------------------
	url          : None 
	port         : 8080 
	action_url   : None 
	user_agent   : Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.0 Safari/537.36 
	html_file    : None 
	external_js  : None 
	--------------------
Нужно заполнить первые 3 пункта 
пишем команды через set
set url << и сайт начиная с https:// >>>
set port 5050
set action_url   << и сайт начиная с https:// >>>
run
ГОТОВО !!!
сайт склонирован !!! 
теперь подключаем Ngrok и готово 
*********************************************************

НО ЗА ЭТИ ДЕЙСТВИЯ ИМЕЕТЬСЯ СТАТЬЯ ПО КИБЕРПРИСТУПНОСТИ 
РАБОТАЙТЕ ЧЕРЕЗ МАШИНУ С РЕПОЗИТОРИЕМ Linux Kodachi https://www.digi77.com/linux-kodachi/
И В НЕЙ НАПУСКАЕМ МАШИНУ С РЕПОЗИТОРИЕМ Linux Parrot OS https://parrotlinux.org/
УДАЧИ !!!!

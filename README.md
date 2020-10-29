# DOCKER LEMP - "базовый" вариант

* **hosts** ‒ хранятся конфиги nginx
* **images** ‒ образы докера
    * **php** ‒ пример созданного образа (PHP7.4)
* **logs** ‒ хранение логов nginx
* **mysql** ‒ файлы бд
* **www** ‒ файлы бд
    * **default.test** ‒ пример созданного хоста
    
Не забывайте добавлять в hosts:

* Windows: `%windir%\System32/drivers/etc`
* Linux: `/etc/hosts`

Название хостов (`server_name`) из конфигов созданных в директории `hosts/`

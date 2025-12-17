1) В директории text_processing создать файл employers с содержимым
```
iivanov ivanovi@tech.com +19081348639
+79755609446 vsidorov sidorovv@mai.ru chief
head of designers mpetryakova petryakovamm@tech.com
lipatovv developer +21230953853 vlipatov@tech.com
developer kfisun fisunkv@gmai.com
```
2) С помощью grep и регулярные выражения получить из файла employers все номера телефонов
3) С помощью grep и регулярные выражения получить из файла employers все e-mail
4) В директории text_processing создать файл office_inventory с содержимым
```
iivanov-pc 192.168.10.5 Linux (Debian 11)
vvpanin-pc 192.168.10.10 Windows (10)
mgeladzem-mac 192.168.10.6 MacOs (Ventura)
vfilippov-pc 192.168.10.12 Linux (Ubuntu 22.04)
osipov-laptop 192.168.10.15 Windows (8)
```
5) С помощью grep и регулярные выражения получить из файла office_inventory все ip-адреса
6) С помощью grep и регулярные выражения получить из файла office_inventory все весии операцилнных систем
7) В директории text_processing создать файл apache_error.log с содержимым
```
[Sun Jan 19 10:00:01.123456 2025] [core:error] [pid 1234:tid 140123456789824] [client 192.168.1.1:12345] Directory index forbidden by Options directive: /var/www/html/
[Sun Jan 19 10:00:02.123456 2025] [php:error] [pid 1234:tid 140123456789824] [client 192.168.1.1:12345] PHP Warning:  include(nonexistent.php): failed to open stream: No such file or directory in /var/www/html/index.php on line 10
[Sun Jan 19 10:00:03.123456 2025] [core:error] [pid 1234:tid 140123456789824] [client 192.168.1.2:54321] File does not exist: /var/www/html/favicon.ico
[Sun Jan 19 10:00:04.123456 2025] [authz_core:error] [pid 1234:tid 140123456789824] [client 192.168.1.3:67890] AH01630: client denied by server configuration: /var/www/html/private/
[Sun Jan 19 10:00:05.123456 2025] [core:error] [pid 1234:tid 140123456789824] [client 192.168.1.4:13579] Premature end of script headers: cgi-bin/script.cgi
```
8) С помощью grep и регулярные выражения получить из файла apache_error.log ip-адрес клиента
9) С помощью grep и регулярные выражения получить из файла apache_error.log источник записи

<img width="910" alt="image" src="https://github.com/user-attachments/assets/f5defcc5-a34e-4c1d-be8a-11187067d19b" />

10) В директории text_processing создать файл add_conf.conf
```
[allowed_ips]
ip_list = 192.168.1.1,192.168.1.2,10.0.0.1

[integrations]
service_a_url = https://api.service-a.com/v1/
service_b_url = https://api.service-b.com/v1/

[additional]
feature_x_enabled = false
max_connections = 100
```
11) С помощью grep и регулярные выражения получить из файла add_conf.conf все ip-адреса
12) С помощью grep и регулярные выражения получить из файла add_conf.conf все url
Домашнее задание к занятию «ELK»
Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.
![1](https://github.com/user-attachments/assets/a1c58365-737c-4ae5-8992-86feba5dd426)

Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.
![2](https://github.com/user-attachments/assets/2ec33903-e09e-42b5-a2d7-82b3f72cf955)


Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.
![3](https://github.com/user-attachments/assets/d79e774d-2207-4062-a6bc-352f375e27b8)
![4-1](https://github.com/user-attachments/assets/ffb4dbe7-35e3-47f2-b00c-6bd4884bb998)


Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.
![5](https://github.com/user-attachments/assets/e66e610e-7a12-4289-ad65-10627c561553)

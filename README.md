# Домашнее задание к занятию "`ELK`" - `Федоров Павел`



### Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

![[Название скриншота 2](ссылка на скриншот 2)](https://github.com/PavelFedorov84/ELK/blob/main/img/S1.jpg)`


---

### Задание 2. Kibana

Установите и запустите Kibana.

![[Название скриншота 2](ссылка на скриншот 2)](https://github.com/PavelFedorov84/ELK/blob/main/img/S2.jpg)`

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

![[Название скриншота 2](ссылка на скриншот 2)](https://github.com/PavelFedorov84/ELK/blob/main/img/S3.jpg)`

---

### Задание 4 Filebeat

![[Название скриншота 2](ссылка на скриншот 2)](https://github.com/PavelFedorov84/ELK/blob/main/img/S4.jpg)`

---

### Задание 5*. Доставка данных

Настройте поставку лога в Elasticsearch через Logstash и Filebeat любого другого сервиса , но не Nginx. Для этого лог должен писаться на файловую систему, Logstash должен корректно его распарсить и разложить на поля.


Источник логов postgresql.

![[Название скриншота 2](ссылка на скриншот 2)](https://github.com/PavelFedorov84/ELK/blob/main/img/S5.jpg)`



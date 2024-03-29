# Домашнее задание к занятию "`Система мониторинга Zabbix Часть 2`" - `Гак Ярослав`

В практике есть 4 основных и 5 дополнительных (со звездочкой) заданий. Основные задания нужно выполнять обязательно, со звездочкой - по желанию и его решение никак не повлияет на получение вами зачета по этому домашнему заданию, при этом вы сможете глубже и/или шире разобраться в материале.

### Цели задания



1.Научитья создавать свои шаблоны в Zabbix, добавлять в Zabbix хосты и связывать шаблон с хостами
2.Научиться составлять кастомный дашборд
3.Научиться создавать UserParameter на Bash
4.Научиться создавать Python-скрип, добавляться в него UserParameter и прикреплять к шаблону
5.Научиться создавать Vagrant-скрипты для Zabbix Agent

---

### Задание 1

#### Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста
#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции
2. В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
3. Создайте Item который будет собирать информацию об загрузке CPU в процентах
4. Создайте Item который будет собирать информацию об загрузке RAM в процентах
Требования к результатам
Прикрепите в файл README.md скриншот страницы шаблона с названием «Задание 1»
![alt text](https://github.com/Anudora41/sys-hw-zb2/blob/main/zab%202%20задание%201.png)
---

### Задание 2

#### Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2
#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
5. Прикрепите за каждым хостом шаблон Linux by Zabbix Agent
6. Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов
Требования к результатам

Результат данного задания сдавайте вместе с задание 3

---

### Задание 3

#### Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent
#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции
2. Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
3. Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
4. Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона
Требования к результату

Прикрепите в файл README.md скриншот страницы хостов, где будут видны привязки шаблонов с названиями «Задание 2-3». Хосты должны иметь зелёный статус подключения
![alt text](https://github.com/Anudora41/sys-hw-zb2/blob/main/задание%202-3.0.png)
![alt text](https://github.com/Anudora41/sys-hw-zb2/blob/main/задание%202-3.1.png)
![alt text](https://github.com/Anudora41/sys-hw-zb2/blob/main/задание%202-3.png)

---

### Задание 4

#### Создайте свой кастомный дашборд
#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В разделе Dashboards создайте новый дашборд
3. Разместите на нём несколько графиков на ваше усмотрение.
Требования к результату

Прикрепите в файл README.md скриншот дашборда с названием «Задание 4»
![alt text](https://github.com/Anudora41/sys-hw-zb2/blob/main/задание%204.png)

---


# Домашнее задание к занятию «Уязвимости и атаки на информационные системы» - Мильдзихов Сергей


### Задание 1

Скачайте и установите виртуальную машину Metasploitable: https://sourceforge.net/projects/metasploitable/.

Это типовая ОС для экспериментов в области информационной безопасности, с которой следует начать при анализе уязвимостей.

Просканируйте эту виртуальную машину, используя **nmap**.

Попробуйте найти уязвимости, которым подвержена эта виртуальная машина.

Сами уязвимости можно поискать на сайте https://www.exploit-db.com/.

Для этого нужно в поиске ввести название сетевой службы, обнаруженной на атакуемой машине, и выбрать подходящие по версии уязвимости.

Ответьте на следующие вопросы:

- Какие сетевые службы в ней разрешены?
- Какие уязвимости были вами обнаружены? (список со ссылками: достаточно трёх уязвимостей)
  

### Ответ

Был установлен Metasploitable
Стандартные логин и пароль

Логин по умолчанию: msfadmin
Пароль по умолчанию: msfadmin

![Screnshot](1.png)

![Screnshot](2.png)

![Screnshot](3.png)

![Screnshot](4.png)

- Какие сетевые службы в ней разрешены?



- Какие уязвимости были вами обнаружены? (список со ссылками: достаточно трёх уязвимостей)

  
### Задание 2

Проведите сканирование Metasploitable в режимах SYN, FIN, Xmas, UDP.

Запишите сеансы сканирования в Wireshark.

Ответьте на следующие вопросы:

- Чем отличаются эти режимы сканирования с точки зрения сетевого трафика?
- Как отвечает сервер?


### Ответ



University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP-Telephony](https://itmo-ict-faculty.github.io/ip-telephony/)

Year: 2024/2025

Group: K34212

Author: Shagvalieva Ekaterina Albertovna

Lab: Lab2

Date of create: 07.04.2025

Date of finished: 27.04.2025

# Лабораторная работ №2 "Конфигурация voip в среде Сisco packet tracer"

## Цель работы

Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

## Ход работы

Часть 1.
Для начала работы воспроизводим схему сети из задания.

![image](https://github.com/user-attachments/assets/7111f8c8-5d8e-4212-8de6-39060b10693f)

В режиме конфигурации поменяем маршрутизатору имя, настроим интерфейс и DHCP-пул для голосовой сети.

![image](https://github.com/user-attachments/assets/09d21ff3-8b1f-416c-9bd2-e0a2b43fea57)

На коммутаторе поднимем интерфейсы.

![image](https://github.com/user-attachments/assets/e7c88b1b-4d62-478a-a65e-11271625cd00)

И проверим связь между телефонами.

![image](https://github.com/user-attachments/assets/91cfbcf2-4500-4fd6-84dd-c9d0487f3fe9)

![image](https://github.com/user-attachments/assets/8887a8c6-6c5c-4d81-b328-bf30d29391b6)

Связь установлена, значит подключение произведено корректно.

Часть 2.

Для начала 2 части была воспроизведена схема сети.

![image](https://github.com/user-attachments/assets/e73839c7-99d3-4b5b-b943-a955f448a61b)

Настраиваем VLAN и интерфейсы.

![image](https://github.com/user-attachments/assets/1c9d6a63-d9ec-4cba-9d57-a6eb694693aa)

Настраиваем интерфейсы с инкапсуляцией dot1Q для VLAN.

![image](https://github.com/user-attachments/assets/c8385208-68b0-463f-a9d5-b44424ceb165)

Настраиваем Cisco CallManager Express.

![image](https://github.com/user-attachments/assets/76526501-c1e8-4e5e-b813-05ee2d76f9db)

Затем проверяем подключение телефонов. Все телефоны Connected.

![image](https://github.com/user-attachments/assets/b8fa9ff1-c42b-401d-9c75-6511de568953)

![image](https://github.com/user-attachments/assets/dedb47b2-3224-4db0-adcb-402c6f389e3e)

![image](https://github.com/user-attachments/assets/c120a2eb-48a1-4fa8-b363-30f8e0ac00fc)

И пинги между компьютерами.

![image](https://github.com/user-attachments/assets/09711986-8a33-4698-8afc-05e2d94c910b)

![image](https://github.com/user-attachments/assets/45ebc949-9b3a-4b54-813b-fb7fe9775601)

Все прошло успешно, значит работа была выполнена конкретно.

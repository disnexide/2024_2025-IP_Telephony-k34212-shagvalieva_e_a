University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP-Telephony](https://itmo-ict-faculty.github.io/ip-telephony/)

Year: 2024/2025

Group: K34212

Author: Shagvalieva Ekaterina Albertovna

Lab: Lab1

Date of create: 28.03.2025

Date of finished: 28.03.2025

# Лабораторная работ №1 "Базовая настройка ip-телефонов в среде Сisco packet tracer"

## Цель работы

Изучить рабочую среду Cisco Packet Tracer, ознакомить- ся с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.

## Ход работы

Для выполнения первой части работы составим схему в Cisco Packet Tracer.

![image](https://github.com/user-attachments/assets/bf2ee736-8fd0-4c78-8414-b5cff645c6a5)

Затем для всех PC вручную назначим IP-адреса: для PC0 192.168.1.2, для PC1 192.168.1.3 и так далее.

![image](https://github.com/user-attachments/assets/5bfb5536-90bf-45f7-b79c-12617b2a404c)

А для комутаторов назначим имена (Switch1-4) и поднимем интерфейсы, по которым выполнены подключения к компьютерам или другим коммутаторам.

![image](https://github.com/user-attachments/assets/e64c00bf-dcf8-4eed-93e2-773f73c188e5)

Для проверки правильности настройки отправим ping-запросы с одного компьютера на другой. Сначала - с PC0 на PC1. 

![image](https://github.com/user-attachments/assets/4e91b00b-056a-4cd3-a993-f7d75e103745)

Затем - с PC6 на PC4.

![image](https://github.com/user-attachments/assets/cf9097f3-8931-48a8-a586-bf92c3005e4e)

Пинги проходят успешно, значит сеть настроена корректно.

Приступим ко второй части лабораторной работы.

Составленная топология выглядит следующим образом.

![image](https://github.com/user-attachments/assets/11a8f69d-f020-4046-9f34-9d81f0ec730e)

Первым делом настраиваем маршрутизатор и интерфейс на нем.

![image](https://github.com/user-attachments/assets/a470f124-6f5e-4bba-bf5c-ebd2c911d4a5)

Далее переходим к настройке коммутаторов: назначаем имя, создаем VLAN для телефонов.

![image](https://github.com/user-attachments/assets/c5350c09-5ab9-46e3-a126-bc279e335f03)

И привязываем порты IP-телефонов к VLAN.

![image](https://github.com/user-attachments/assets/99277e3d-ec0e-4bf6-8346-fd24a51c082d)

На маршрутизаторе настрваиваем интерфейсы.

![image](https://github.com/user-attachments/assets/4c02331f-b521-4a58-a6f3-39c3067fa361)

Настраиваем DHCP сервер, Cisco CallManager Express и телефоны.

![image](https://github.com/user-attachments/assets/70fe08aa-ba78-48df-a9bb-c4ae7780cfe7)

Осталось проверить, как проходят звонки с телефонов:

![image](https://github.com/user-attachments/assets/337aefa2-024a-432f-a1c7-a027f46caa6e)

![image](https://github.com/user-attachments/assets/1a97fe90-50bf-4cae-87ea-70a7c74568d6)

## Вывод

В ходе выполнения лабораторной работы была настроена сеть IP-телефонии с использованием маршрутизатора Cisco 2811, коммутатора и IP-телефонов Cisco 7960 в среде Cisco Packet Tracer.

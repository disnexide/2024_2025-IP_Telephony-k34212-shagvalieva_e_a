University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP-Telephony](https://itmo-ict-faculty.github.io/ip-telephony/)

Year: 2024/2025

Group: K34212

Author: Shagvalieva Ekaterina Albertovna

Lab: Lab3

Date of create: 10.04.2025

Date of finished: 13.04.2025

# Лабораторная работ №3 "Использование Asterisk в качестве SIP proxy"

## Цель работы

Изучить программный комплекс Asterisk. Настройка Asterisk для локальных звонков.

## Ход работы

Для начала работы настроим среду с помощью следюущих команд:

'''
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential wget curl git nano sudo
sudo apt install -y libxml2-dev libncurses5-dev libnewt-dev libsqlite3-dev libssl-dev uuid-dev libjansson-dev libedit-dev pkg-config
cd /usr/src
sudo wget https://github.com/pjsip/pjproject/archive/refs/tags/2.13.tar.gz
sudo tar -xvzf 2.13.tar.gz
cd pjproject-2.13
sudo ./configure CFLAGS="-fPIC" --prefix=/usr --libdir=/usr/lib64
sudo make
sudo make install
sudo ldconfig
cd /usr/src
sudo wget http://downloads.asterisk.org/pub/telephony/asterisk/asterisk-20-current.tar.gz
sudo tar -xvzf asterisk-20-current.tar.gz
cd asterisk-20.*/
sudo contrib/scripts/install_prereq install
sudo ./configure
sudo make
sudo make install
sudo make samples
sudo make config
sudo ldconfig
'''

И проверим, что все установилось корректно и подключимся к консоли Asterisk.
'''
asterisk -V  
sudo systemctl start asterisk
sudo systemctl enable asterisk
sudo asterisk -rvvv 
'''


University: ITMO University <br/>
Faculty: FICT <br/>
Course: IP-telephony <br/>
Year: 2022/2023 <br/>
Group: K34212 <br/>
Author: George Zavarzin <br/>
Lab: Lab4 <br/>
Date of create: 15.04.2023 <br/>
Date of finished: 15.04.2023 <br/>

# Лабораторная работа №4 "Построение сети ip-телефонии между удаленными маршрутизаторами"


## Описание
Для выполнения данной лабораторной работы были выполнены следующие шаги: Была собрана топология, состоящая из маршрутизаторов, коммутаторов, IP-телефонов.

![image](https://user-images.githubusercontent.com/60888284/232197181-199f9635-9208-44f4-93a5-3c2805a1f05d.png)

## Цель работы:
Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т


## Ход работы:

1. Были изменены имена маршрутизаторов и настроены интервейсы fa0/0 

![image](https://user-images.githubusercontent.com/60888284/232197320-95d267a0-384a-4f7f-9657-cdcd7acde3a6.png)

2. Были настроены интерфейсы se0/3/0 

![image](https://user-images.githubusercontent.com/60888284/232197437-c6eb8e6f-b86b-4a37-84ed-c5f972a0175b.png)

3. Был настроен пул адресов для dhcp-сервера 

![image](https://user-images.githubusercontent.com/60888284/232197475-acb7d644-2cbe-4a19-8701-c0db08f8898b.png)

4. Настроен протокол rip для динмаической маршрутизации 

![image](https://user-images.githubusercontent.com/60888284/232197501-f4cf0fce-fa07-4f86-b0ef-2ded902bb546.png)

5. Была настроена ip-телефония 

![image](https://user-images.githubusercontent.com/60888284/232197524-0f2462ed-367a-4ddc-ae86-2ada618bf497.png)

6. Были выданы номера для теелфонов 

![image](https://user-images.githubusercontent.com/60888284/232197542-0db3ac4c-af0f-4e24-8e4d-7c8ce0fcfbff.png)
![image](https://user-images.githubusercontent.com/60888284/232197661-090ee8db-f7ad-4000-a5e1-b188939ff8b3.png)

7. Выполнили проверку работы и связаности устройств 

![image](https://user-images.githubusercontent.com/60888284/232197898-9cb3dedc-fb79-4eb1-94e5-4564a63021f7.png)

## Выводы:
Таким образом, была настроена сеть IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т

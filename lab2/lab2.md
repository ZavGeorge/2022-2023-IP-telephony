University: ITMO University <br/>
Faculty: FICT <br/>
Course: IP-telephony <br/>
Year: 2022/2023 <br/>
Group: K34212 <br/>
Author: George Zavarzin <br/>
Lab: Lab2 <br/>
Date of create: 20.03.2023 <br/>
Date of finished: 20.03.2023 <br/>

# Лабораторная работа №2 "Конфигурация voip в среде Сisco packet tracer" 

## Описание
Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены все узлы устройств. Предварительно удалить все преды- дущие конфигурационные файлы на маршрутизаторах Cisco 2811, на коммутаторе Cisco catalyst 3560

## Цель работы:
Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960
   
   
## Ход работы:

1. Построена топология сети, которая включает телефоны, коммутаторы и роутер.
![image](https://user-images.githubusercontent.com/60888284/226296632-e30bcfc3-7647-4b58-b6dd-a40ded82c9c9.png)

2. В конфигурационном режиме изменено название маршрутизатора на CMERouter, назначен пароль и отключен синтаксис ввода слов от DNS серверов. Был настроен интерфейс fa0/0

![image](https://user-images.githubusercontent.com/60888284/226296947-8d987f1d-4e73-4067-989c-8c14456eacfc.png)
![image](https://user-images.githubusercontent.com/60888284/226296972-451e6226-6b59-46d2-97bf-5859a47deeea.png)

3. Настроен DHCP сервер для передачи голоса и данных на маршрутизаторе. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе

![image](https://user-images.githubusercontent.com/60888284/226297315-bb72ccd8-d5c0-4c15-b551-8274eb9e6dac.png)
![image](https://user-images.githubusercontent.com/60888284/226297330-e2c73c8c-df2e-4d5c-b352-463f4643b35b.png)

4. Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны. Настроены IP-телефоны и соединены с коммутатором 
![image](https://user-images.githubusercontent.com/60888284/226297557-ccdfffa9-416b-476f-851a-7bbecdbdcb94.png)
![image](https://user-images.githubusercontent.com/60888284/226297570-41135b9c-5790-4037-ba76-a996f2c66374.png)

5. Проверены звонки между телефонами
![image](https://user-images.githubusercontent.com/60888284/226297590-32fa198e-2d44-4329-a4b8-8bdbb5d0fdbc.png)

6. Создана новая топология
![image](https://user-images.githubusercontent.com/60888284/226297748-37a982a7-3211-4e4e-ba09-c41fc080420c.png)

7. Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны, также задан маршрут по умолчанию 

![image](https://user-images.githubusercontent.com/60888284/226298121-cb0b932f-a038-42d3-b41a-afb0747fa432.png)
![image](https://user-images.githubusercontent.com/60888284/226298137-3b2290ff-38ed-4f07-8b18-361d63e33093.png)
![image](https://user-images.githubusercontent.com/60888284/226298524-2edd0cb4-4915-4c11-bc73-8706b93f0412.png)

8. Настроили интерфейс управления коммутатороом в сети VLAN через назначение диапазона портов

![image](https://user-images.githubusercontent.com/60888284/226298756-9204c4db-515e-4ef0-9252-fe5ae60f3194.png)

9. Создали логические подынтерфейсы для VLAN 10, VLAN 20 и VLAN 30
![image](https://user-images.githubusercontent.com/60888284/226299076-19b9ea46-f5e5-4cb2-b9f4-066642931bf8.png)
![image](https://user-images.githubusercontent.com/60888284/226299154-5e0100fb-7f0b-493e-b4ac-fa68551b87a2.png)
![image](https://user-images.githubusercontent.com/60888284/226299172-6ccca578-ebdb-4a9e-8688-55fa18f75c3e.png)


10. Исключили из пула адрес интерфейса маршрутизатора и DNS-сервера

![image](https://user-images.githubusercontent.com/60888284/226299266-6788e265-65ac-4d5b-89bb-e952628332f6.png)

11. Настроили DHCP сервера для передачи голоса и данных на маршрутизаторе. Настроили теоефонный сервис 

![image](https://user-images.githubusercontent.com/60888284/226299385-d78f2cc4-a627-4535-96b4-0a682cdd25a7.png)
![image](https://user-images.githubusercontent.com/60888284/226299474-441948f4-3fdc-4349-be98-8a3c4d9e31a5.png)

12. Проверили работу телефонов

![image](https://user-images.githubusercontent.com/60888284/226299834-95cd9c37-72b1-4204-8913-bef43aafb6bd.png)

![image](https://user-images.githubusercontent.com/60888284/226301144-6fb41a47-bd2c-4e6a-b636-6de157093e75.png)

## Выводы:
Таким образом, была изучена схема настройки IP-телефонии с помощью CallManager Express

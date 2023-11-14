University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4113c <br>
Author: Shirshov Artem Sergeevich <br>
Lab: Lab2 <br>
Date of create: 14.11.2023 <br>
Date of finished: 16.11.2023 <br>

# Лабораторная работа №2 "Развертывание веб сервиса в Minikube, доступ к веб интерфейсу сервиса. Мониторинг сервиса."
### Описание
В данной лабораторной работе вы познакомитесь с развертыванием полноценного веб сервиса с несколькими репликами.

### Цель работы
Ознакомиться с типами "контроллеров" развертывания контейнеров, ознакомится с сетевыми сервисами и развернуть свое веб приложение.

### Ход работы
В процессе выполнения работы были выполнены следующие шаги:
1. Создан Deployment с двумя репликами контейнера из указанного образа <br>
![image](images/picture1.png)
2. Создан Service для доступа к подам <br>
![image](images/picture2.png)
3. Запущен Deployment и Service <br>
![image](images/picture3.1.png)
![image](images/picture3.2.png)
4. Проверен статус подов <br>
![image](images/picture4.png)
5. Проброшены порты через minikube <br>
![image](images/picture5.png)
6. Запущено веб-приложение <br>
![image](images/picture6.1.png)
![image](images/picture6.2.png)
7. Проверены логи <br>
![image](images/picture7.png)

### Вывод
Таким образом, ознакомились с типами "контроллеров" развертывания контейнеров, ознакомились с сетевыми сервисами и развернули свое веб приложение. <br>
![image](images/picture8.png)
University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4113c <br>
Author: Shirshov Artem Sergeevich <br>
Lab: Lab1 <br>
Date of create: 07.11.2023 <br>
Date of finished: 09.11.2023 <br>

# Лабораторная работа №1 "Установка Docker и Minikube, первый манифест."
### Описание
Это первая лабораторная работа в которой вы сможете протестировать Docker, установить Minikube и развернуть свой первый "под".

### Цель работы
Ознакомиться с инструментами Minikube и Docker, развернуть свой первый "под".

### Ход работы
В процессе выполнения работы были выполнены следующие шаги:
1. Установлен Docker, установлен и запущен Minikube; <br>
![image](images/picture1.png)
2. Скачан образ контейнера; <br>
![image](images/picture2.png)
3. Запущен контейнер из скачанного образа; <br>
![image](images/picture3.png)
4. Создан и запущен "под"; <br>
![image](images/picture4.png)
5. Создана служба (Service) для "пода"; <br>
![image](images/picture5.png)
6. Задано прямое соединение портов между локальным портом и портом службы; <br>
![image](images/picture6.png)
7. Для аутентификации использовался токен, найденный в логах; <br>
![image](images/picture7.png)
8. Полученный результат; <br>
![image](images/picture8.png)
9. Сгенерирован yaml файл для развертывания "пода"; <br>
![image](images/picture9.png)

### Вывод
В результате выполнения работы были изучены инструменты Docker, Minikube, был развернут "под" и получен yaml файл для его развертывания.
![image](images/picture10.png)
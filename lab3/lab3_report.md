University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4113c <br>
Author: Shirshov Artem Sergeevich <br>
Lab: Lab3 <br>
Date of create: 22.11.2023 <br>
Date of finished: 23.11.2023 <br>

# Лабораторная работа №3 "Сертификаты и "секреты" в Minikube, безопасное хранение данных."
### Описание
В данной лабораторной работе вы познакомитесь с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube.

### Цель работы
Познакомиться с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube.

### Ход работы
В процессе выполнения работы были выполнены следующие шаги:
1. Создан ConfigMap с требуемыми переменными <br>
![image](images/picture1.png)
2. Создан ReplicaSet, в который переданы указанные переменные <br>
![image](images/picture2.png)
3. Создан tls секрет, в который прописаны созданные приватный и публичные ключи <br>
![image](images/picture3.png)
4. Создан Service для приложения <br>
![image](images/picture4.png)
5. Создан Ingress. В него переданы ключи из секрета, а также указан путь, по которому будет доступно приложение <br>
![image](images/picture5.png)
6. Произведен деплой всего вышеуказанного <br>
![image](images/picture6.png)
7. Включен Ingress в Minikube <br>
![image](images/picture7.png)
8. Проложен сетевой туннель между локальным компьютером и кластером Kubernates <br>
![image](images/picture8.png)
9. Для пользователей MacOS/Windows необходимо указывать в hosts localhost, что и было сделано. Хотя в документации сказано, что в hosts надо указывать ip minikube. Как позже выяснилось, эта информация актуальна только для Linux <br>
![image](images/picture9.png)
10. Проверка работоспособности приложения в браузере. Все работает <br>
![image](images/picture10.png)
11. Сертификат <br>
![image](images/picture11.png)

### Вывод
Таким образом, ознакомились с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube <br>
![image](images/picture12.png)
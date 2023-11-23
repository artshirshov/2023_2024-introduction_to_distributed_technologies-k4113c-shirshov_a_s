University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4113c <br>
Author: Shirshov Artem Sergeevich <br>
Lab: Lab4 <br>
Date of create: 23.11.2023 <br>
Date of finished: 23.11.2023 <br>

# Лабораторная работа №4 "Сети связи в Minikube, CNI и CoreDNS"
### Описание
Это последняя лабораторная работа в которой вы познакомитесь с сетями связи в Minikube. Особенность Kubernetes заключается в том, что у него одновременно работают underlay и overlay сети, а управление может быть организованно различными CNI.

### Цель работы
Познакомиться с CNI Calico и функцией IPAM Plugin, изучить особенности работы CNI и CoreDNS.

### Ход работы
В процессе выполнения работы были выполнены следующие шаги:
1. Запущен minikube с подключенным плагином calico и двумя нодами <br>
![image](images/picture1.png)
2. Проверено наличие подов calico <br>
![image](images/picture2.png)
3. Проверено наличие двух разных нод <br>
![image](images/picture3.png)
4. Созданы лэйблы нодам <br>
![image](images/picture4.1.png)
![image](images/picture4.2.png)
5. Удален дефолтный ippool <br>
![image](images/picture5.1.png)
![image](images/picture5.2.png)
6. Созданы собственные ippool <br>
![image](images/picture6.png)
7. Проверено, что наши ippool созданы и с ними все верно <br>
![image](images/picture7.png)
8. Развернуто приложение с сервисом <br>
![image](images/picture8.png)
9. Проверены ip адреса. Адреса из тех ippool, которые мы создали, следовательно, все настроено верно <br>
![image](images/picture9.png)
10. Подключились к одному из подов и пинганули соседний. Пинг прошел, значит связь между ними есть <br>
![image](images/picture10.png)
11. Проброшены порты сервиса <br>
![image](images/picture11.png)
12. Открыто приложение в браузере. Все отобразилось корректно <br>
![image](images/picture12.png)

### Вывод
В результате выполнения лабораторной работы, ознакомились с CNI Calico и функцией IPAM Plugin, а также изучили особенности работы CNI и CoreDNS. <br>
![image](images/picture13.png)
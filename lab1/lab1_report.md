# Лабораторная работа №1 «Обзор Google Cloud и исследование основных сервисов»  
University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FTMI](https://itmo.ru/ru/viewfaculty/87/fakultet_tehnologicheskogo_menedzhmenta_i_innovaciy.htm)  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)  
Year: 2024/2025  
Group: U4125  
Author: Tereshina Elina Sergeevna  
Lab: Lab2  
Date of create: 29.04.2025  
Date of finished:  
## Ход работы  
## Создание сервиса Cloud Run  
Сначала я зашла в раздел Cloud Run. Там отображаются все доступные сервисы.  
![1](/img/2.1.png)  
  
Затем я приступила к созданию Cloud Run из представленного дефолтного сервиса Hello. Указала порт 8080.  
![2](/img/2.2.png)  
  
Сервис создался.
![3](/img/2.3.png)  
  
## Тестирование сервиса Cloud Run  
Затем я перешла по ссылке и убедилась, что все работает.  
![4](/img/2.4.png)  
  
## Смотрим логи и метрики  
Перешла в соответствующие разделы.  
В логах мы видим статус GET 200, что говорит об успехе.  
![5](/img/2.5.png)  
  
В метриках мы видим различные графики.  
![6](/img/2.6.png)  
![7](/img/2.7.png)  
  
## Смена порта Cloud Run  
Я зашла в настройки и поменяла порт с 8080 на 8090.  
![8](/img/2.8.png)  
  
Сервис был успешно запущен.  
![9](/img/2.9.png)  
  
## Переключение трафика  
Затем я переключила трафик, разделив его 50/50.  
![10](/img/2.10.png)  
  
## Логи и метрики  
В логах видим наш порт 8090.
![11](/img/2.11.png)  
  
Здесь я уже научилась менять масштаб графиков, поэтому метрики можно рассмотреть более детально.  
![12](/img/2.12.png)  
![13](/img/2.13.png)  
  
## Удаление ресурсов  
В конце я все удалила.

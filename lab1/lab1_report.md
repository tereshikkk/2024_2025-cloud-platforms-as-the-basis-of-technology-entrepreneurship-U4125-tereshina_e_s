# Лабораторная работа №1 «Обзор Google Cloud и исследование основных сервисов»  
University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FTMI](https://itmo.ru/ru/viewfaculty/87/fakultet_tehnologicheskogo_menedzhmenta_i_innovaciy.htm)  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)  
Year: 2024/2025  
Group: U4125  
Author: Tereshina Elina Sergeevna  
Lab: Lab1  
Date of create: 29.04.2025  
Date of finished:  
## Ход работы  
## Создание Service Account  
Сначала я зашла в раздел IAM & Admin — Service Account и создала аккаунт с ролью Storage Admin. Это оказалось важным шагом, так как без выбранной роли возникнет ошибка доступа.  
![1](/img/1.1.png)  

## Создание Compute Engine  
Затем я приступила к созданию Compute Engine (виртуальная машина) с заданными характеристиками: Machine type e2-micro в режиме spot.  
![2](/img/1.2.png)  
  
Машина создалась и работала.
![3](/img/1.3.png)  
  
## Подключение к машине через SSH  
Я подключилась к машине и выполнила команды по созданию новой папки и копированию в нее необходимых файлов. Все прошло успешно и файлы были скопированы.  
![4](/img/1.4.png)  
![4](/img/1.5.png)  
  
## Смена роли на Compute Viewer  
Я перешла в раздел редактирования Service Account и установила новую роль —  Compute Viewer.  
![5](/img/1.6.png)  

Затем я опять подключилась к машине, однако выполнить копирование файлов не вышло. С данной ролью мы видим ошибку AccessDeniedException 403 — нам не хватает прав.  
![5](/img/1.7.png)  
  
## Удаление ресурсов  
В конце я все удалила.

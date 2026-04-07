Ильина Алина, группа: АДЭУ-221 Вариант 8.

# Отчет по лабораторной работе №2

Тема данных: Доставка: Standard Class. Основной фильтр: Standard Class
Доп. задание 1: Статистика продаж	
Доп. задание 1: Анализ по городам

# Цель работы
Получить практические навыки создания сложного ETL-процесса, включающего динамическую загрузку файлов по HTTP, нормализацию базы данных, обработку дубликатов и настройку обработки ошибок с использованием Pentaho Data Integration (PDI).

# Ход выполнения работы
## 1. Подготовка базы данных
Выполнен SQL-скрипт для создания таблиц:

orders — таблица "Заказы"  
customers — таблица "Клиенты"  
products — таблица "Товары"  

![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_1.PNG)

## 2. Создание трансформации Orders
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_2.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_3.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_4.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_5.PNG)
### Доп. задание 1: задаем фильтр
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_6.PNG)

![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_7.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_8.PNG)

## 3. Создание трансформации Customers
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_9.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_10.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_11.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_12.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_13.PNG)

## 4. Создание трансформации Products
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_14.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_15.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_16.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_17.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_18.PNG)

## 5. Создание Job
![]()
![]()
![]()
![]()
![]()
![]()



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

## 5. Доп. задания:
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_28.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_29.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_30.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_31.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_32.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_33.PNG)

## 6. Создание Job
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_19.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_20.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_21.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_22.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_23.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_24.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_25.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_26.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/etl_2_27.PNG)

## Результаты
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_1.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_2.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_3.PNG)

также результаты по дополнительным заданиям:

![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_4.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_6.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_5.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_2/img/p_7.PNG)

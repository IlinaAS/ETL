Ильина Алина, группа АДЭУ-221
# Вариант 8
Лабораторная работа 1.1 Установка и настройка ETL-инструмента. Создание конвейеров данных
Название: Загрузка данных веб-аналитики из CSV в MySQL: данные оо посещаемости сайта.
Инструмент: Pentaho Data Integration (Kettle)

Запуск Пентахо:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_1.PNG)
Загрузка данных:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_2.PNG)
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_3.PNG)
Загрузка файла (Csv file input):
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_4.PNG)
Проводим проверку названий (select values) столбцов для базы данных (snake-case):
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_5.PNG)
Проводим отбор столбцов (Memory group by):
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_6.PNG)
Задаем фильтры:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_7.PNG)
Заполнение полей Value mapper:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_8.PNG)
Вкладка Table order:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_9.PNG)
Результат:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_10.PNG)
Результат в phpMyAdmin:
![](https://github.com/IlinaAS/ETL/blob/main/lab_1/img/etl_11.PNG)

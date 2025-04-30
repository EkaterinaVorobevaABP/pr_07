# pr_07
## Цель: 
научиться импортировать и экспортировать данные в базу данных SQL. Работа включает в себя загрузку данных из внешних источников в таблицы базы данных, а также экспорт данных из базы данных в различные форматы. Необходимо научиться работать с внешними данными, преобразовывать их в нужный формат и интегрировать с существующими таблицами в базе данных.
## Вариант 5
1.	Первоначально для выполнения заданий импортируем библиотеку psycopg2, подключаемся к серверу базы данных, создаем базу данных medical_db и таблицу hospital, заполним ее данными
 ![image](https://github.com/user-attachments/assets/6646c0f4-c23d-4842-ae13-dfb102dabab5)

Далее запросом создаем таблицу doctor, заполняем ее данными

2.	Следующим шагом подключимся к базе данных и распечатаем ее версию:
 ![image](https://github.com/user-attachments/assets/2ca07e29-a8db-4003-b54e-f242f3baa562)


3.	Получаем информацию о больнице и докторе используя уникальный идентификатор
 ![image](https://github.com/user-attachments/assets/092c3efa-5b20-4054-9201-9c0f2ce9eb84)


4.	Получаем список врачей по специальности и зарплате
![image](https://github.com/user-attachments/assets/636ee0ee-f78f-445a-b8b7-7d40229722aa)
 

5.	Получим список врачей из определенной больницы 
 ![image](https://github.com/user-attachments/assets/4b8098bf-fa0c-49b1-bc2b-269315a78864)


6.	Обновляем данные врачу с ID 101:
 ![image](https://github.com/user-attachments/assets/212f38b7-bcdc-4e44-bd74-43f7a8565327)


## Индивидуальные задания
1.	Создайте таблицу "Department" с полями "ID", "NAME"
 
 ![image](https://github.com/user-attachments/assets/303dc7e4-0ef3-469c-bc40-8ddd8151f358)
 ![image](https://github.com/user-attachments/assets/48762b08-0b74-40a8-b2bc-08ae5268cf40)


Проверим наличие всех необходимых таблиц:
 ![image](https://github.com/user-attachments/assets/54b5d34f-1534-481b-b503-2d7ba2fdf24b)

2.	Вставьте запись с новой моделью телефона в таблицу "mobile"
 ![image](https://github.com/user-attachments/assets/d40370dd-bfb7-4db1-bb31-f5d874a0f3e2)

 ![image](https://github.com/user-attachments/assets/19dd1b4e-695f-4751-94d9-808b56f15523)



3.	Получите список всех докторов, работающих в больнице с ID=4.
 
![image](https://github.com/user-attachments/assets/b47f44dc-00e9-485a-9285-665cdb99029b)

4.	Сохраните список врачей по специальности в новый CSV-файл
После импорта библиотеки и задания функций def вводим:
 ![image](https://github.com/user-attachments/assets/8eeb7474-6eb5-4b2a-a2a3-08dc93179be9)

Функция «copy to» помогает получить csv файл. Далее загрузим его в Yandex DataLens для построения визуализации

5.	Постройте круговую диаграмму для процентного распределения врачей по специализациям.
После загрузки данных на BI-платформу создадим подключение, датасет и следующий чарт:
 
![image](https://github.com/user-attachments/assets/3969644c-ef41-45bc-8a27-9575444a2aff)

[https://datalens.yandex.cloud/wizard/8jvkz12bsb9wu-doctors-krugovaya-diagramma](https://datalens.yandex/8jvkz12bsb9wu)
Ссылка на чарт Yandex DataLens

В репозиторий загружены все необходимые файлы: ERD-диаграмма, SQL-скрипт, файл VS code, все задания выполнены!

## Вывод: 
в ходе работы были изучены методы работы с данными для их экспорта и импорта, осуществлены создание базы данных, таблиц и визуализации на BI-платформе.

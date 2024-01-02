# labs-sql-python
Кравченко Евгений Константинович, 2023, 4 курс 4 группа 
Справочник Клуб:  Название(текст), год снования(число)
Справочник Игрок: Имя(текст), Фамилия(текст), Дата рождения(дата), Клуб(зависимость), зарплата(число с плавающей точкой)

SQLite
CREATE TABLE Club ( club_id INTEGER PRIMARY KEY, name TEXT, create_year INTEGER );
CREATE TABLE Player ( player_id INTEGER PRIMARY KEY, name TEXT, surname TEXT, birth_dt DATE, club_id INTEGER, salary DECIMAL(10,2), FOREIGN KEY (club_id) REFERENCES Club(club_id) );

![image](https://github.com/Ewgen0107/labs-sql-python/assets/91210688/6dcf9bd4-a92c-493c-87fe-2a04392b97c7)

![image](https://github.com/Ewgen0107/labs-sql-python/assets/91210688/ce52c674-cbc7-42e3-b657-2c347736f1c5)

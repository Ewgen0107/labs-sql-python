# labs-sql-python
Кравченко Евгений Константинович, 2023, 4 курс 4 группа 
Справочник Клуб:  Название(текст), год снования(число)
Справочник Игрок: Имя(текст), Фамилия(текст), Дата рождения(дата), Клуб(зависимость), зарплата(число с плавающей точкой)

SQLite
CREATE TABLE Club ( club_id INTEGER PRIMARY KEY, name TEXT, create_year INTEGER );
CREATE TABLE Player ( player_id INTEGER PRIMARY KEY, name TEXT, surname TEXT, birth_dt DATE, club_id INTEGER, salary DECIMAL(10,2), FOREIGN KEY (club_id) REFERENCES Club(club_id) );



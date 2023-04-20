# used_cars

| **PK (ID)** |    **columns**   | **data_types** |
|:-----------:|:----------------:|:--------------:|
| 1           | brand            | VARCHAR(25) NOTNULL    |
| 2           | model            | VARCHAR(30) NOTNULL    |
| 3           | price            | MEDIUMINT NOTNULL      |
| 4           | km               | MEDIUMINT NOTNULL      |
| 5           | transmission     | VARCHAR(15) NULL       |
| 6           | year             | YEAR NOTNULL           |
| 7           | fuel             | VARCHAR(15) NOTNULL    |
| 8           | horsepower       | SMALLINT NULL          |
| 9           | type             | VARCHAR(20) NULL       |
| 10          | doors            | TINYINT NULL           |
| 11          | air_conditioning | TINYINT NULL           |
| 12          | radio            | TINYINT NULL           |
| 13          | bluetooth        | TINYINT NULL           |
| 14          | color            | VARCHAR(20) NULL       |
| 15          | interior_color   | VARCHAR(20) NULL       |
| 16          | tyres            | VARCHAR(25) NULL       |
| 17          | cruise_control   | TINYINT NULL           |
| 18          | inspection       | DATE NULL              |
| 19          | speed            | TINYINT NULL           |
| 20          | license_plate    | VARCHAR(20) NOTNULL    |
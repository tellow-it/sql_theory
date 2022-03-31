# sql_theory
theory

Базы данных и SQL

1.Урок. Основные понятия, настройка PostgreSQL
SQL - язык для работы с базой данных

Типы баз данных:  

1. Сетевые и иерархические - данные организованы в виде иерархии/сети (Microsoft)
2. Реляционые - данные хранятся в виде таблиц, связанных между собой (SQL)
3. Нереляционные - данные хранятся в неструктурированном виде на распределенном кластере серверов (Big Data, NoSQL)
Relation(Отношение)

Представление данных в виде таблиц 

![image](https://user-images.githubusercontent.com/84245620/160932282-1b5b3813-4153-4cbf-a808-7237cbd6fd8a.png)

История

![image](https://user-images.githubusercontent.com/84245620/160932457-0d0e52dc-9f4e-4532-8797-7221416b2cce.png)

Популярные системы

![image](https://user-images.githubusercontent.com/84245620/160932691-9175454a-b727-4134-860b-9e30283e518a.png)

SQL в нереляционных базах данных

![image](https://user-images.githubusercontent.com/84245620/160932775-34915367-9bf8-4497-acfe-1287b4e040bc.png)

Причины популярности SQL

1. Строгая математическая основа
2. Стандарты
3. Многие знают SQL
 
![image](https://user-images.githubusercontent.com/84245620/160932821-720059e5-0d22-40b4-abde-ae4695fc1a18.png)

5432

Настройка PostgreSQL

https://www.asozykin.ru/posts/demo_database_sql_foundation

2.Урок.Основы SELECT
SELECT - ВЫБОР 
* - все элементы
FROM - откуда

![image](https://user-images.githubusercontent.com/84245620/161017566-a41bdb19-aaab-401b-9717-b143ba6f6fc9.png)

Если нужно конкретные столбцы, то 
SELECT далее название столбцво через запятую

![image](https://user-images.githubusercontent.com/84245620/161017752-a1920e89-a8e6-47e0-9c03-a45fe0843436.png)

Псевдонимы для столбцов

AS

![image](https://user-images.githubusercontent.com/84245620/161018209-b9b5eb8e-0c02-4d89-8542-c49ca1d1f95e.png)

Выбор уникальных значений столбцов в SELECT

параметр DISTINCT

![image](https://user-images.githubusercontent.com/84245620/161018417-f45327d1-a27d-4f6e-b1e3-010e8c3eec17.png)

Ограничение количества извлекаемых строк

команда LIMIT

![image](https://user-images.githubusercontent.com/84245620/161018865-6228dbd8-4958-4b2b-a74e-bfe86bf989e6.png)

Итог

![image](https://user-images.githubusercontent.com/84245620/161022318-8e40a46f-a848-4809-a3a3-993fe516b7d5.png)

3.Урок. Фильтрация

Для фильтрации используется команда WHERE

WHERE название столбца оператор строка для фильтрации

![image](https://user-images.githubusercontent.com/84245620/161022591-927a355e-7685-4e93-9b14-68581700c24b.png)

Оперторы WHERE

![image](https://user-images.githubusercontent.com/84245620/161022662-8918f1ff-1c8c-4d4e-8ab6-52aa155c2845.png)

Оператор BETWEEN

![image](https://user-images.githubusercontent.com/84245620/161028004-7efa49c1-5e0b-43f8-8c1a-161f4b889419.png)

Оператор IN

![image](https://user-images.githubusercontent.com/84245620/161028334-710b3155-aaa9-439d-8a55-65bd12ff2d4d.png)

Оператор LIKE

![image](https://user-images.githubusercontent.com/84245620/161028736-81e02be6-0eb5-4577-a99f-619f5a7453af.png)


![image](https://user-images.githubusercontent.com/84245620/161028667-d348bd85-a5aa-4627-8545-949c4afb6a72.png)

Логические операторы AND OR NOT

AND

![image](https://user-images.githubusercontent.com/84245620/161029069-fe2f973e-b732-410c-8aac-8bde66088bfb.png)

OR

![image](https://user-images.githubusercontent.com/84245620/161029360-7bf2167c-b8bf-43c5-b694-e10337278d49.png)

![image](https://user-images.githubusercontent.com/84245620/161029383-8b0e8b71-9c6a-4a4a-9316-9c7aec89343d.png)

NOT 

![image](https://user-images.githubusercontent.com/84245620/161029567-03a8f0d3-e133-4eca-99ef-ffe99416cf92.png)

Итог

![image](https://user-images.githubusercontent.com/84245620/161029619-a327f92c-29b7-4ba7-a781-eebd65bcaf4f.png)


4.Урок. Сортировка в SQL

Сортировка данных в SELECT

команда ORDER BY

![image](https://user-images.githubusercontent.com/84245620/161035926-61ebdf14-a221-42d2-b556-ebf4e6c3d1bb.png)

Порядок сортировки 

ASC по возрастанию 

DESC по убыванию

![image](https://user-images.githubusercontent.com/84245620/161036785-3869b2c1-555d-4d41-ab52-b0aca988fa27.png)


Сожно сортировать по нескольким столбцам указав их через запятую

Итог

![image](https://user-images.githubusercontent.com/84245620/161037292-69ed2fde-4553-4b77-ae6f-5496ace9188f.png)

5.Урок. Создание таблиц

Создание таблицы

![image](https://user-images.githubusercontent.com/84245620/161041238-d2053559-ca3b-411d-829f-1367d091368d.png)


Типы данных

![image](https://user-images.githubusercontent.com/84245620/161038175-e962e36b-57ad-425a-a6e5-7d88145a7d6a.png)

Первичный ключ - это поле, которое используется для обеспечения уникальности данных в таблице. 

Автозаполнение первичного ключа 

![image](https://user-images.githubusercontent.com/84245620/161038935-b3a7218d-3d7b-4bfc-817f-1901cd5757e1.png)

Удаление таблицы

DROP TABLE название_таблицы

Изменение таблиц

![image](https://user-images.githubusercontent.com/84245620/161041760-2aeaf82c-c4e7-40ae-872a-a2d811db1232.png)

Итог

![image](https://user-images.githubusercontent.com/84245620/161042257-b1879ef7-6eff-48d8-a5ea-e630719afc0f.png)

6.Урок. Вставка и изменение данных

INSERT INTO 
VALUE

![image](https://user-images.githubusercontent.com/84245620/161044853-b57ce2d4-ed93-48e4-856e-030c99253dda.png)

Изменение данных в таблице

UPDATE 

![image](https://user-images.githubusercontent.com/84245620/161045014-67110be0-0e90-4f28-a53d-f10d72a1fa77.png)

![image](https://user-images.githubusercontent.com/84245620/161045438-9253bef1-1d15-4381-ba40-1e4d0b14f7f4.png)

Удаление данных из таблицы 

DELETE

![image](https://user-images.githubusercontent.com/84245620/161045581-2eb48e95-c857-46a1-a76b-fa3906fa2cc5.png)


Итог

![image](https://user-images.githubusercontent.com/84245620/161045920-34529f1d-7948-4bb4-bb2c-398fb1673fc4.png)

7.Урок. Группировка данных 

GROUP BY 

![image](https://user-images.githubusercontent.com/84245620/161051698-fb3a75bb-5d8a-4cf1-aced-b64624f3b51b.png)

![image](https://user-images.githubusercontent.com/84245620/161053128-5a6a85be-3da1-41cd-b3d9-7da2fc7259f7.png)

Итог

![image](https://user-images.githubusercontent.com/84245620/161053324-8d5010ac-aee8-45a4-89f3-038cb170c1d6.png)

8.Урок. Агрегатные функции

Агрегатные функции 

![image](https://user-images.githubusercontent.com/84245620/161054632-ab03d6a5-aec4-46d7-bb1e-9b5a62432cc5.png)

Использование агрегатных функций

![image](https://user-images.githubusercontent.com/84245620/161055140-3e5a6558-e8d8-4a16-a08f-a0a67d16a013.png)

![image](https://user-images.githubusercontent.com/84245620/161055543-28558807-5f21-41ec-91c2-0c4c8e074256.png)

Итог

![image](https://user-images.githubusercontent.com/84245620/161057205-ddd5e2e0-7202-492f-b60a-2d6e8de0e39a.png)

9.Урок. Группировка и фильтрация. Having

Having

![image](https://user-images.githubusercontent.com/84245620/161058021-0fe3a75b-922d-497f-94b1-4d501b1abd74.png)


Мы не можем использовать условии в Where т.к на том этапе мы работаем со всей таблицей

Итог

![image](https://user-images.githubusercontent.com/84245620/161058051-7875e2be-150b-4091-af8a-1a6562a14a09.png)
















 

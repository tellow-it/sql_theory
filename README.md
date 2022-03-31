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
4. 
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

3.Урок Фильтрация

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





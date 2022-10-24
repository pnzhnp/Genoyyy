# Геннадий Сухорослов
SELECT * FROM users (вывести из все из таблицы с пользователями)
SELECT * FROM users WHERE name='Олег' (найти записи с именем олег)
SELECT * from grades (вывести все оценки)
SELECT * FROM users JOIN grades on users.user_id=grades.user_id (вывести пользователей и их оценки)
SELECT  COUNT(*) FROM information_schema.tables WHERE table_schema = 'p518238_lyc' (Сколько таблиц в базе данных)
SELECT COUNT(*) FROM users (сколько чловек в таблице)

# T-SQL

### Темы:

* Концепция нормализации данных, Нормальные формы
* Создание таблиц, Выбор типов данных
* Создание ограничений: NOT NULL, UNIQUE, CHECK, DEFAULT, PRIMARY KEY, FOREIGN KEY
* Моделирование отношений: один к одному, один ко многим, многие ко многим, Primary Key & Foreign Key
* Работа с оператором SELECT, Использование операторов WHERE, INNER/LEFT/RIGHT/CROSS JOIN, GROUP BY, HAVING, DISTINCT
* Работа агрегатными функциями: SUM, MIN, MAX, AVG, COUNT
* Модификация данных с использованием INSERT, UPDATE, DELETE операторов
* Работа с операторами UNION, UNION ALL, INTERSECT, EXCEPT
* Работа с хранимыми процедурами, функциями и триггерами
* Использование SQL профайлера
* Индексы
* Работа с оконными функциями
* Работа с СTE, Рекурсивные CTE
* Анализ плана выполнения запроса
* Работа с транзакциями, ACID, Уровни изоляций транзакций, Snapshot, Мертвые блокировки

### **Контрольные вопросы:**

* Какие нормальные формы Вам знакомы?
* Сравните нормализацию и денормализацию баз данных.
* Как моделируется отношение "многие ко многим" в MS SQL?
* В чем разница между Primary Key и Foreign Key?
* В чем разница между операторами LEFT JOIN vs INNER JOIN?
* В чем разница между операторами CROSS JOIN и CROSS APPLY?
* В чем отличия Кластерных индексов от Некластерных?
* Для чего применяется оператор INCLUDE при создании некластерного индекса?
* Какие уровни изоляций транзакций существуют?
* Опишите свойства ACID.
* Как избегать мертвых блокировок при работе с транзакциями?
* В чем разница между временными таблицами и CTE?

### Источники:

* Книга [T-SQL Fundamentals](https://www.amazon.com/T-SQL-Fundamentals-3rd-Itzik-Ben-Gan/dp/150930200X)
* [РАБОТА С SQL SERVER PROFILER. ПРИМЕРЫ НАСТРОЙКИ ТРАССИРОВОК](https://ausevich.ru/subd/rabota-s-profiler-sql-server-primery-nastrojki-trassirovok/)
* [Описания кластеризованных и некластеризованных индексов](https://docs.microsoft.com/ru-ru/sql/relational-databases/indexes/clustered-and-nonclustered-indexes-described?view=sql-server-ver15)
* [14 вопросов об индексах в SQL Server, которые вы стеснялись задать](https://habr.com/ru/post/247373/)
* [Отображение действительного плана выполнения](https://docs.microsoft.com/ru-ru/sql/relational-databases/performance/display-an-actual-execution-plan?view=sql-server-ver15)
* [Изучение плана запроса в SQL](http://sql-ex.ru/blogs/optimization/exploring_query_plans_in_sql.html)
* [Snapshot Isolation in SQL Server](https://www.sqlshack.com/snapshot-isolation-in-sql-server/)


# Распределённые системы и Микросервисы

### Темы:

* Что такое распределенная система?
* Вертикальное и горизонтальное масштабирование
* Теорема CAP
* Концепция балансировки нагрузки
* Кеширование в распределенных системах
* Репликации баз данных
* Выбор между Performance vs scalability, Latency vs throughput, Availability vs consistency в распределенных системах
* Consistency patterns: Weak consistency, Eventual consistency, Strong consistency
* Availability patterns: Active-passive Failover, Active-active Failover, Master-slave replication, Master-master replication
* Построение микросервисной архитектуры
* Распределенные транзакции, 2PC, Saga Pattern
* Миграция с монолита на микросервисы, Шаблон Strangler

### Контрольные вопросы:

* В чем разница между Вертикальным и горизонтальным масштабированием?
* В чем смысл теоремы CAP?
* Какие существуют алгоритмы балансировки нагрузки?
* Опишите шаблон кеширования Cache-aside.
* В чем разница между SQL и No-SQL
* Что такое Eventual consistency?
* Как добиться транзакционности в микросервисной архитектуры?
* Опишите идею шаблона Strangler.

### Источники:

* [Lecture 9 Scalability Harvard Web Development David Malan](https://www.youtube.com/watch?v=-W9F__D3oY4)
* [Горизонтальное и вертикальное масштабирование веб приложений](https://server-gu.ru/scaling-out-vs-scaling-up/)
* [CAP Theorem: Revisited](https://robertgreiner.com/cap-theorem-revisited/)
* [The System Design Primer](https://github.com/donnemartin/system-design-primer)
* [Load balancer](https://github.com/donnemartin/system-design-primer#load-balancer)
* [The System Design Primer, Cache](https://github.com/donnemartin/system-design-primer#cache)
* [Scalability for Dummies - Part 3: Cache](https://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
* [he System Design Primer, Replications](https://github.com/donnemartin/system-design-primer#relational-database-management-system-rdbms)
* [The System Design Primer, Trade offs](https://github.com/donnemartin/system-design-primer#performance-vs-scalability)
* [The System Design Primer, Consistency Patterns](https://github.com/donnemartin/system-design-primer#consistency-patterns)
* [The System Design Primer, Availability Patterns](https://github.com/donnemartin/system-design-primer#availability-patterns)
* [Статьи Мартина Фаулера по Микросервисам](https://martinfowler.com/articles/microservices.html)
* [Книга Building Microservices: Designing Fine-Grained Systems 1st Edition by Sam Newman](https://www.amazon.com/Building-Microservices-Designing-Fine-Grained-Systems/dp/1491950358)
* [Patterns for distributed transactions within a microservices architecture](https://developers.redhat.com/blog/2018/10/01/patterns-for-distributed-transactions-within-a-microservices-architecture/)
* [Pattern: Saga](https://microservices.io/patterns/data/saga.html)
* [Monolith to Microservices Using the Strangler Pattern](https://dzone.com/articles/monolith-to-microservices-using-the-strangler-patt)


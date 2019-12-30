# Шаблоны уровня доступа к данным

### Темы:

* Объектно-реляционное отображение \(ORM\)
* Шаблон Репозиторий \(Repository\)
* Шаблон Спецификация \(Specification\)
* Шаблон Единица работы \(Unit Of Work\)
* Шаблон Объект запроса \(Query Object\)
* Шаблон Активная запись \(Active Record\)
* Шаблон Репозиторий в DDD
* Оптимистическая блокировка, Пессимистическая блокировка

### Контрольные вопросы:

* Какую проблему решает технология ORM?
* Как сочетаются вместе шаблоны Unit of Work и Repository?
* Можно ли совмещать шаблоны Repository и Specification?
* В чем смысл шаблона Specification?
* Нужно ли создавать репозиторий для моделей, которые не являются корнями агрегатов?
* Является ли шаблон Active Record анти-шаблоном?
* Как работает механизм Оптимистической блокировки?

### Источники:

#### Книги:

* [Patterns of Enterprise Application Architecture](https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420)

#### Статьи:

* [ORM \(Object-Relational Mapping\)](https://ru.bmstu.wiki/ORM_%28Object-Relational_Mapping%29)
* [Domain-Driven Design: Repository](https://blog.byndyu.ru/2011/01/domain-driven-design-repository.html)
* [CRUD Operations Using the Generic Repository Pattern and Unit of Work in MVC](https://habr.com/ru/post/238737/)
* [Unit of Work Design Pattern](https://www.codeproject.com/Articles/581487/UNIT-of-Work-Design-Pattern)
* [Dapper + QueryObject, как замена ORM](https://blog.byndyu.ru/2013/03/dapper-queryobject-orm.html)
* [Работа с Dapper + Query Object](http://blog.antidasoftware.com/2014/08/dapper-queryobject.html)


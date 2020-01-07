# Многопоточность и Асинхронность

### Темы:

* Понимание терминов Процесс, Поток, Пулл потоков, Мертвая блокировка
* Понимание концепций Многопоточного программирования, Асинхронного программирования и Параллелизма
* Класс Thread: Start, Join, Abort, Sleep \| Фоновые и активные потоки
* Ключевые слова async и await, Syncronization Context
* Класс Task, Использование методов Run, Delay, WhenAny, WhenAll, ContinueWith, Обработка исключений, AggregateException
* Необходимость использования синхронизации потоков \| Простая синхронизация потоков: ключевое слово lock, Monitor.Enter, Monitor.Exit, Interlocked
* PLINQ: Parallel.For, Parallel.ForEach, AsParallel, AsOrdered, WithCancellation
* Сихнронизация потоков: Mutex, Semaphor, AutoResetEvent, ManualResetEvent, Reader/Writer Locks, volatile
* Использование потокобезопасных коллекций: ConcurrentBag, IProducerConsumerCollection, ConcurrentDictionary
* Тестирование асинхронных методов
* Task Scheduling
* Неизменяемые коллекции: ImmutableList, ImmutableDictionary, ImmutableHashSet

### Контрольные вопросы:

* Что такое Виртуальное адресное пространство?
* Почему большое количество параллельных потоков могут ухудшить производительность приложения?
* В чем разница между Потоком и Процессом?
* Когда возникает Мертвая блокировка?
* В чем разница между Thread.Sleep и Task.Delay?
* В чем разница между Lock и Monitor?
* В чем разница между Thread и Task?
* Почему неизменяемые типы являются потокобезопасными?
* В чем разница между Многопоточным и Асинхронным программированием?
* Когда нужно думать о синхронизации потоков?
* В чем разница между механизмами синхронизации Mutex и Semaphore?
* Почему примитивные операции инкремента или присваивания нужно синхронизировать классом Interlocked?
* Что такое ReaderWriterLockSlim?
* Как создать потокобезопасный Синглтон?
* Является ли класс Lazy&lt;T&gt; потокобезопасным?

### **Источники:**

**Книги:**

* [C\# in a Nutshell](http://www.albahari.com/nutshell/bookcontents.aspx) by Joe Albahari, Ben Albahari
* CLR via C\# by Jeffrey Richter
* [Concurrency in C\# Cookbook](https://www.amazon.com/Concurrency-Cookbook-Asynchronous-Multithreaded-Programming/dp/149205450X/ref=dp_ob_title_bk) by Stephen Cleary

**Статьи:**

* [Основы многопоточности в .NET Framework](https://habr.com/ru/company/nix/blog/260745/)
* [Введение в PLINQ](https://docs.microsoft.com/ru-ru/dotnet/standard/parallel-programming/introduction-to-plinq)
* [Многопоточное vs асинхронное программирование](https://ru.stackoverflow.com/questions/445768/%d0%9c%d0%bd%d0%be%d0%b3%d0%be%d0%bf%d0%be%d1%82%d0%be%d1%87%d0%bd%d0%be%d0%b5-vs-%d0%b0%d1%81%d0%b8%d0%bd%d1%85%d1%80%d0%be%d0%bd%d0%bd%d0%be%d0%b5-%d0%bf%d1%80%d0%be%d0%b3%d1%80%d0%b0%d0%bc%d0%bc%d0%b8%d1%80%d0%be%d0%b2%d0%b0%d0%bd%d0%b8%d0%b5)
* [.NET: Инструменты для работы с многопоточностью и асинхронностью](https://habr.com/ru/post/452094/)




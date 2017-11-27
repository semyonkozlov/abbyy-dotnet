﻿# Курс .NET

- Система выставления [оценок](course-2017-1/readme.md)
- Посещаемость [студентов](course-2017-1/attendance.md)
- Список [заданий](exercises/exercises.md)
- Таблица [успеваемости](course-2017-1/performance-table.md)
- Гайд по воркфлоу в [git+github](exercises/git-help.md).

---

- 1 [.NET](course/1-net.md#net)
  - .NET Framework, CLR
  - .NET Core, .NET Standard
  - IDE
  - Nuget
- 2 [Types](course/2-types.md#overview)
  - Namespaces
  - Primitive types: Integers, Float numbers, etc
  - Операторы: Арифметические, поразрядные, операторы с присваиванием, логические операторы, Тернарный, null-операторы
  - Контроль переполнения
  - Приведение типов
  - `switch`, Pattern Matching
  - Ссылочные и значимые типы
    - Размещение в стеке и куче
    - `System.Object`
- 3 [Value types](course/3-value-types.md#value-types)
  - `struct`
  - `Nullable`, `Guid`, `DateTime`, `DateTimeOffset`
  - `enum`
- 4 [Classes](course/4-classes.md#classes)
  - Members, properties, constructors, methods
  - Модификаторы доступа
  - `static`, `readonly`, `const`
  - Наследование, полиморфизм, `abstract`, `sealed`
  - Интерфейсы
  - Перегрузка операторов и преобразований типов
  - Extension methods
  - Аттрибуты
- 5 [GC](course/5-gc.md#gc)
  - Сборка мусора
  - Финализаторы
  - Внешние ресурсы, `Dispose`, `IDisposable` pattern
- 6 [Generic](course/6-generic.md#generic)
  - Generic
    - Generic methods, classes, interfaces, delegates
    - Open / Closed constructed types
    - Ограничения обобщений
    - Ковариантность и контрвариантность
  - `Tuple`, `ValueTuple`, Deconstructors
- 7 [Strings](course/7-strings.md#strings)
  - `char`, `string`, `StringBuilder`, Encoding
- 8 [Collections](course/8-collections.md#collections)
  - Control flow: `for`, `foreach`, `IEnumerable`, `yield`
  - Collections: `Array`, `List<T>`, `Dictionary<TKey,TValue>`, `SortedList`, `SortedDictionary`, `HashSet`, etc
  - Равенство: `Equals`, `GetHashCode`, `IEquatable<T>`, `IEqualityComparer<T>`, `IComparable<T>`
- 9 [Delegates](course/9-delegates.md#delegates)
  - Delegates, Generic delegates, Events, Lambdas, Closures
- 10 [LINQ](course/10-linq.md#linq)
  - Отложенные и неотложенные запросы
  - Стандартный и Query Expressions синтакис запросов
- 11 Обработка ошибок
  - Exception
  - throw / try / catch / finally
  - Debug / Trace
- 12 Многопоточность и ассинхронность
  - Проблемы многопоточности
  - Примитивы синхронизации
  - Thread / Threadpool
  - TPL. Класс Task, Continuation, Cancellation
  - async / await, SyncronizationContext

---

- Сериализация данных
  - JSON
  - XML
- Ввод / вывод
  - Потоки
  - Чтение и запись текстовой информации
  - Работа с файловой системой. System.IO
- Reflection
- Работа с базами данных
  - ADO.Net
  - Entity Framework
  - Simple mapper: dapper, linq2db
- Принципы и паттерны проектирования
  - SOLID
  - Связь классов: наследование, ассоциация, композиция, агрегация
  - Dependency Injection, IOC, управление зависимостями
  - Тестируемость приложения, unit-test, Moq
  - Паттерны: Singleton, Factory, Strategy, Facade, Repository
- Работа в web
  - Http в .Net, класс HttpClient
  - ASP.Net MVC Core

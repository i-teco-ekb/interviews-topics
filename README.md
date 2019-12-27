# Темы для интервью кандидатов

## Java

### Общее
1. Интерфейсы и абстрактные классы
1. Генерики
1. Пулы констант

### Object
1. Какие методы в Object
1. Контракт между hashCode и equals

### Коллекции

1. Какие коллекции знаете: Maps, Sets, Lists, Queues, Dequeues
1. Связи между классами коллекций
1. Устройство HashMap, производительность в терминах O различных операций
1. Устройство TreeMap, производительность в терминах O различных операций
1. Устройство и типы Set
1. Требования к ключу для TreeMap: compareTo
1. Различие между ArrayList и LinkedList, применение LinkedList
1. Конкуренция с коллекциями

### Исключения
1. Основные классы исключений
1. Назначение кастомных исключений
1. Проверяемые и не проверяемые исключения

### Многопоточность
1. wait, notify, notifyAll
1. syncronized
1. Методы Thread: run, join, yield
1. Прерывание потоков
1. Доступ к памяти, volatile
1. Java Memory Model
1. Monitor, happens before
1. Методы гарантирования синхронизации памяти между потоками: volatile, syncronized, Atomic*, final, function (псевдооднопоточность)
1. Locks: ReentrantLock, ReentrantReadWriteLock
1. Executors
1. Синхронизация потоков: Semaphore, CountDownLatch, CyclicBarrier, Exchanger<V>, Phaser
1. Принцип работы Atomic* классов, отличия от Volatile и syncronized

## Spring
1. Жизненный цикл бинов
1. Способы получения бинов в классе: Autowired, constructor. Преимущества и недостатки методов.
1. Как получить prototype из singleton бина
1. Реализация AOP
1. Прямой доступ к методам класса и через бины: proxy

## JPA

1. Уровни кэширования, назначение кэшей
1. Типы связей таблиц
1. В какой момент читаются связанные данные: Eager, lazy
1. Проблема N+1 и способы ее решения: fetch size, cache, join query

## SQL

### Транзакции
1. Уровни изоляции транзакций
1. Отличие друг от друга различных уровней
1. Транзакции в Spring, JPA и Hibernate
1. Программыне транзакции
1. Декларативные транзакции
1. Вложенные транзакции

### Агрегации
1. Назначение Having, отличие от where
1. Порядок обработки операторов и доступ к псевдонимам

## JMS
1. Что такое JMS
1. Какие провайдеры JMS знаете
1. Основное назначение систем очередей
1. Отличие RabbitMQ от Kaffka

## JVM & GC
1. Какие JVM знаете?
1. Особенности исполнения кода в Hotspot
1. AOT и JIT компиляция
1. Устройство памяти в JVM: Stack, Heap, Code
1. Какие сборщики мусора знаете: Serial, Parallel, Concurrent Mark Sweep (CMS), Garbage-First (G1)

## Шаблоны проектирования
1. Принципы ООП
1. SOLID
1. DRY
1. Основные шаблоны: builder, factory, adapter, decorator/proxy, visitor, chain of responsibilities
1. Чем отличается адаптер от декоратора

## Docker
1. Что такое контейнера
1. Что такое образ и в чем отличие от контейнера
1. Файловая система в образе докера

## Микросервисы
1. Причины разбивки монолита на микросервисы
1. Реализация транзакций в микросервисной архитектуре
1. Saga-pattern
1. Cirquit Breaker
1. Способы реализации обмена между микросевисами, преимущества и недостатки

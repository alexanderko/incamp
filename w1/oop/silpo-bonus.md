---
description: >-
  Задание на закрепление основ ООП и написание Unit тестов. В ходе решения
  предпологаеться использование
---

# 👨‍💻 Баллы в Сильпо

Приложение расчета итогов по чеку и количеству начисленных балов в Сильпо. Исходный код на Java [https://gitlab.in6k.com/meetup/oop-workshop](https://gitlab.in6k.com/meetup/oop-workshop). 

## Задачи

### Часть 1 – Знакомство

1. [Создать проект с подержкой xUnit тестов](https://docs.microsoft.com/ru-ru/dotnet/core/testing/unit-testing-with-dotnet-test). Краткое описание атрибутов и доступных методов проверки в [https://xunit.net/docs/comparisons](https://xunit.net/docs/comparisons)
2. Для каждого исходного [коммита в репозитории](https://gitlab.in6k.com/meetup/oop-workshop/-/commits/master), начиная с [первого](https://gitlab.in6k.com/meetup/oop-workshop/-/commit/1642d713b5d364c716281ccbe485fc9c300e115f) 
   1. Просмотреть соответствующую [видео-запись](https://nas.in6k.com/share.cgi?ssid=08fToBx) процесса написания существующего кода. По ходу видео рассматривается процесс написание Unit тестов и суть принципа инкапсуляции. Постепенно подходим к наследования и полиморфизму.  
   2. Написать соответствующий тест, как в коммите и на видео
   3. Написать реализацию кода, что бы тест прошел
3. Завершить рефаторинг кода – Разнести полиморфное поведение по классам `AnyGoodsOffer` и `FactorByCategoryOffer`

### Часть 2 – Шаблон проектирования Template Method

1. Реализовать возможность использовать предложения до закрытия чека \(во время покупки\)
2. Реализовать проверку на срок годности предложения. Использовать шаблон проектирования Template Method .

#### **Материалы**

1. \*\*\*\*[Что такое Шаблон проектирования](https://refactoring.guru/design-patterns/what-is-pattern)
2. [Зачем изучать шаблоны](https://refactoring.guru/design-patterns/why-learn-patterns)
3. [Каталог шаблонов](https://refactoring.guru/design-patterns/catalog)
   1. [Порождающие](https://refactoring.guru/design-patterns/creational-patterns)
   2. [Структурные](https://refactoring.guru/design-patterns/structural-patterns)
   3. [Поведенческие](https://refactoring.guru/design-patterns/behavioral-patterns)
4. Шаблон [Template Method](https://refactoring.guru/design-patterns/template-method)

### **Часть 3 – Шаблон проектирования Strategy**

1. Реализовать начисление баллов за покупку конкретной торговой марки или продукта
2. Реализовать предложение, которое дает скидку на продукт \(50% скидки, подарок за 1 у.е\).
3. Устранить дублирование кода и проблему комбинирования вознаграждения \(`Reward`\) и условия его применения \(`Condition`\) с помощью шаблона проектирования Strategy.
   1. Выделить интерфейс `Reward` и реализовать типы flat\(+amount балов\), factor\(\*factor балов\) и скидку
   2. Выделить интерфейс `Condition` и реализовать `TotalCost`, `CostByCategory` и по производителю/конкретному товару.

#### Материалы

1. Шаблон [Strategy](https://sourcemaking.com/design_patterns/strategy)
2. Фото финальной диаграммы классов и аудио запись ее рисования находиться в [папке с видео](https://nas.in6k.com/share.cgi?ssid=08fToBx). 
   1. 10-2019-07-04-strategy-pattern.jpg – диаграмма классов
   2. 10-2019-07-04-strategy-pattern.mp3 – аудио запись лекции




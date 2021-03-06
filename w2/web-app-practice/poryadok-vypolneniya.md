# Порядок выполнения

К выполнению задания подходим в описанной ниже последовательности. По каждому этапу \(пункту списка\) получаем отклик ментора и потом переходим к следующему. Если в течении 30 минут отклика нет – предупреждаем ментора и переходим к следующему. 

## Приоретизация и проектирание

1. Подготовить список ключевых, самых часто используемых возможностей приложения исходя из своего понимания бизнес области
2. Нарисовать на личточке или в редакторе UML диаграмму бизнес сущностей

## Реализация

Для каждой ключевой функции приложения:

1. Создать в Git ветку с коротким порядковым номер а кратким в 2-3 слова названием фичи. К примеру `1-search-apartments` для приложения "Отель".  Дальше комитить не реже, чем после каждого следующего шага
2. Создать и описать классы моделей
3. Настроить возможность работать с репозиторием моделей \(для Entity Framework описать их в DbContext;  для Spring Data создать интерфейс репозитория\)
4. Создать миграцию
5. Создать сервис
6. Описать схематически \(HTTP методы и пути\) минимально необходимый для работы функционала REST API приложения
7. Создать контроллер
8. Влить ветку в master после финального code review


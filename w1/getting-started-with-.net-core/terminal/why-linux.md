# Навіщо розробнику знати Linux

## Безкоштовна ОС

На базі ядра Linux побудовано багато безкоштовних дистрибутивів операційних систем. Вони використовуютья як на серверах, так на робочих станціях \(ПК\). В нас в компанні силами TSD \(Technical Support Department\) підтримуються дестрибутив Ubuntu. 

## Інструменти розробника

Багато ключових для розробника інструментів не мають графічного інтерфейсу. Вони поставлються у вигляді виконуємих, программм що запускаються в консолі \(терміналі\). Розуміння того, як запустити програму та передати необхідні параметри є ключовим у виріщенні задач кожного дня. 

## Автоматизація

Unix-подібні операційі системи та програми, що виконуються на них, слідують філософії побудови модульних програмного забезпечення, що сприяє його повторнуму використанню. Ось як філософія Unix була [задокументована](https://archive.org/details/bstj57-6-1899/mode/2up) в Bell System Technical Journal за 1878 рік:

> 1. Make each program do one thing well. To do a new job, build afresh rather than complicate old programs by adding new "features".
> 2. Expect the output of every program to become the input to another, as yet unknown, program. Don't clutter output with extraneous information. Avoid stringently columnar or binary input formats. Don't insist on interactive input.
> 3. Design and build software, even operating systems, to be tried early, ideally within weeks. Don't hesitate to throw away the clumsy parts and rebuild them.
> 4. Use tools in preference to unskilled help to lighten a programming task, even if you have to detour to build the tools and expect to throw some of them out after you've finished using them.

Такий підхід в побудові програм зробив можливим автоматизацію складних процесів через використання мінімалісичних, проте гнучких програм, що добре виконують одну задачу. 

Для розробника, це в першу чегру автоматизація зборки пробрами, перевірка її автотестами та автоматичний деплой на сервер. Сам процес розгортання на сервері теж складна может бути складною процедурою в десяток кроків. Автоматизація таких операція мінімізує вплих людського фактору та можливість винекнення помилки по-неуважністі. 

## Робота з віддаленими серверами

Здебільшого сервери, на яких ми розгортаємо наші сервіси, працють на ядрі Linux. Розгортання нових версій додатку та діагностики їхроботи потребує навіків роботи з Linux. Варто зазначити, що на тиких среверах немає графічного інтерфейсу користувачав. Всі операції з ОС та нашим сервісом \(перезапуск, перегляд логів, робота з базою даних\) необхідно виконувати через інтерфейс командного рядку \(Command Line Interface, скорочено CLI\). 


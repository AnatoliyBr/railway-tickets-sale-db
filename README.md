## База данных для сервиса продажи ж/д билетов 
Проект содержит лабораторные работы модуля "Проектирование и реализация баз данных".

## Список лабораторных работ
1. [Определение сущностей логической модели](/lab1/README.md)
2. [Проектирование отношений в логической модели](/lab2/README.md)
3. [Нормализация ER-диаграммы](/lab3/README.md)
4. [Преобразование к третьей нормальной форме](/lab4/README.md)
5. Преобразование отношений многие-ко-многим
6. Построение модели в Oracle SQL Developer Data Modeler (или pgAdmin)
7. Определение типов данных для атрибутов
8. Создание реляционной модели
9. Создание SQL кода

## Техническое задание (Вариант №8)
Необходимо разработать проект для системы продажи ж/д билетов. Требуется реализовать электронную систему продажи ж/д билетов и информационную поддержку сопутствующих аспектов данной сферы посредством создания соответствующего сервиса.

Система позволяет для клиента решать следующие задачи:
1. Приобретение билета
2. Бронирование билета
3. Вернуть билет
4. Посмотреть расписание
5. Посмотреть список мест
6. Регистрация

Внедрение данной системы позволит снизить нагрузку на персонал, обслуживающий продажу билетов из рук в руки, а также связанные с этим эксплуатационные расходы. Функциональность и возможности сервиса расширят возможности по продвижению компании, рекламе, а также проведению различных акций.

Система позволяет решить следующие задачи:
1. Ускорение процесса получения требуемой информации и приобретения билетов
2. Повышение доступности и наглядности предоставляемой информации
3. Снижение расходов на персонал, вовлеченный в процесс продажи билетов и предоставления сопутствующей информации
4. Снижение эксплуатационных расходов на поддержу традиционной системы продажи билетов и предоставления сопутствующей информации
5. Повышение гибкости системы за счет увеличения возможностей по контролю и адаптации к изменениям
6. Расширение списка возможных способов оплаты предоставляемых сервисом услуг

Основные функции системы:
1. Ведение списка рейсов и билетов на них с указанием класса
2. Учёт забронированных мест
3. Ведение архива пассажиров за последний месяц
4. Продажа билетов в оба конца
5. Поиск места на рейс в соответствии с требованиями заказчика
6. Получение списка свободных мест на рейс
7. Выдача информации по конкретному рейсу
8. Получение списка проданных мест
9. Проверка наличия брони по имени клиента и/или названию организации
10. Возможность оплаты при помощи кредитной или дебетовой карты, электронных денег
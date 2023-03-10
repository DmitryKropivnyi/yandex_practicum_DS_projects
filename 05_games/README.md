# Сборный проект. Продажа игр.

Мы работаем в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. 

Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Цель исследования:

Перед нами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и мы планируем кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируем ли мы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.

## Итог исследования:

1. В ходе исследования была проведена предобработка данных, в ходе которой произошли следующие действия:
* Удалены строки с пропусками в столбце **name**
* Изменены типы данных для **user_score** и **uear_of_release**
* Добавлен столбец с суммой продаж по регионам **total_sales**\
    \
В результате был DataFrame, с которым стало удобно работать.
---
2. Проведён исследовательский анализ данных, в результате которого был получен соответствующий актуальный период времени, а также на основе новых данных сделаны следующие выводы:
* Зависимость общих продаж от пользовательских оценок очень слабая, либо можно считать, что вовсе отсутствует, а вот что касаемо оценок критиков, то здесь уже прослеживается умеренная корреляция в большистве случаев, а значит, что люди немного прислушиваются к оценкам критиков
* Проведен анализ жанров игр, в ходе которого самыми перспективными и прибыльными оказались **Shooter, Sports, Platform, Role_Playing, Fighting**
---
3. Составлен портрет пользователя каждого региона с соответствующими результатами :
* Самые популярные платформы в Северной Америке и Европе: **PS4, PS3, XOne, X360, 3DS** 
* Самые популярные платформы в Японии : **3DS, PS3, PSV, PS4, WiiU**
* Самые продаваемые жанры игр в Северной Америке:**Action, Shooter, Sports, Role_playing, Misc**
* Самые продаваемые жанры игр в Европе:**Action, Shooter, Sports, Role_playing, Racing** 
* Самые продаваемые жанры игр в Японии:**Role_playing, Action, Misc, , Fighting, Shooter** 
    \
    *(Платформы и жанры указаны в порядке убывания популярности в данных регионах)*
---
4. Проведено исследование зависимости продаж от рейтинга ESRB:
* В Северной Америке и Европе можно проследить зависимость от данной системы рейтинга. Замечено, что в данных регионах большинство продаж приходится на игры **Для взрослых** и **Для всех**
* Доли продаж игр в Японии **Для подростков**, **Для взрослых** и **Для всех** приблизительно одинаковы, поэтому можно сделать вывод о независимости данного региона от системы ESRB
---
5. Была проведена проверка следующих гипотез:
* Средние пользовательские рейтинги платформ Xbox One и PC одинаковые
* Средние пользовательские рейтинги жанров Action  и Sports  разные
    \
    \
    В результате проверки обе гипотезы были **подтверждены**.

## Стек технологий:

Pandas, matplotlib, numpy, scipy, seaborn

## Статус проекта:

Завершен.
# Определение возраста покупателей

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
* Контролировать добросовестность кассиров при продаже алкоголя.

## Цель исследования:

Постройте модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.

## Итог исследования:

- В данном проекте была использована модель ResNet, предобученная на imageNet.
- Была достигнута необходимая по условиям задачи метрика ниже 7, а именно 6.34
- Данная модель работает корректно и может использоваться в бизнес-задачах,однако стоит отметить,  что для определения возраста младенцев (хотя вряд ли младенцы сами будут приходить в магазин), а также определеление возраста для продажи алкоголя, данную модель не стоит использовать, так как для этих категорий неточность в 7 лет можно считать крайне большой и не даст должного результата.

## Стек технологий:

Pandas, matplotlib, numpy, seaborn, keras

## Статус проекта:

Завершен.
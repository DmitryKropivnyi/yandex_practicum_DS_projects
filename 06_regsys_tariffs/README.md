# Рекомендация тарифов

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

## Цель исследования:

Построим модель с максимально большим значением *accuracy*. Нужно довести долю правильных ответов по крайней мере до 0.75. Проверим *accuracy* на тестовой выборке и получим конечный результат метрики.

## Итог исследования:

Лучшие показатели на тестовой выборке показала модель случайного леса с точностью `0.796`.

Для предсказаний, стоит пользоваться моделью случайного дерева с параметрами: 
* количество - `40`
* глубина - `8`

## Стек технологий:

Pandas, seaborn, scikit-learn.

## Статус проекта:

Завершен.
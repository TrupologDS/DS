# Прогнозирование количества заказов такси на следующий час


## Данные

В наличии были следующие данные:

### Таблица taxi — информация о количестве заказов в определенное время:

    num_orders - число заказов


## Задача

Разработка системы предсказания объема заказа.

## Используемые библиотеки и навыки

*Python*

*Pandas*

*Scikit-learn*

*statsmodels*

*CatBoost*

## Вывод

В данном проекте была проведена работа по анализу временных рядов. Была выявленна сезонность и тренд. Оказалось, что минимальное количество заказов в 6 утра, а максимальное в полночь. К признаковому пространству были добавлены различные технические индикаторы для дальнейшего обучения и тестирования моделей: LinearRegression, RandomForestRegression и CatBoostRegressor. Лучший результат показала Линейная Регрессия.
